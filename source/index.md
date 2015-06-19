---
title: API Reference

language_tabs:
  - Requires


search: true
---

# Security Testing

## dashboard
`
url: '/dashboard',
templateUrl: "views/dashboard.html",
controller: DashboardCtrl
`

```
DirectConvo._id
DirectConvo.msgs.length
DirectConvo.msgs[i].re[i].fullname
DirectConvo.msgs[i].from.fullname
DirectConvo.msgs[i].timestamp
DirectConvo.timestamp
DirectConvo.msgs[i].subject
DirectConvo.msgs[i].text
person.profile.imageUrl
person.relation.type
person.profile.prefs
person._id
person.relation.type
Entry.displayTime
Entry.creator
Entry.data.text
Entry.effective
Event.start
Event.start
Event.timeLeft
Event.topic
Event.description
```

# Organizations

## org.members
`
url: "/{org}/members",
templateUrl: "views/org.html",
controller: OrgMembersCtrl
`

```
Org.profile.prefs.fullname
Org.members
Org.members.patient
Org.members.pro
Org.membershipRequests.pending
Org.permissions
Person.relation.title
Person.profile.prefs.fullname
Person.profile.prefs.address
Person.profile.prefs.phone

```

## org.current
`
url: "/current",
templateUrl: "views/org.html",
controller: OrgCtrl
`

```
Org.members
Org.profile.imageUrl
Org.relation.title
Org.progile.prefs.fullname
Org.profile.prefs.address
Org.profile.prefs.phone
```


# Mailbox

## mailbox.inbox.home
`
url: '',
templateUrl: 'views/mail_list.html',
controller: DirectMsgInboxCtrl
`

```
DirectConvo._id
DirectConvo.msgs.length
DirectConvo.msgs[i]
DirectConvo.msgs[i].from
DirectConvo.msgs[i].from._id
DirectConvo.msgs[i].from.profile.prefs.fullname
DirectConvo.msgs[i].re[i]._id
DirectConvo.msgs[i].re[i].fullname
DirectConvo.msgs[i].subject
DirectConvo.msgs[i].text
DirectConvo.msgs[i].timestamp
DirectConvo.msgs[i].reads
DirectConvo.msgs[i].attachments
```

## mailbox.inbox.view
`
url: '/{id}',
templateUrl: 'views/mail_detail.html',
controller: DirectMsgViewCtrl
`

```
DirectConvo.msgs[i].from._id
DirectConvo.msgs[i].to[i].value._id
DirectConvo._id
DirectConvo.msgs
DirectConvo.msgs[i].from.profile.prefs.fullname
DirectConvo.msgs[i].subject
DirectConvo.msgs[i].text
DirectConvo.msgs[i].re
DirectConvo.msgs[i].re.length
DirectConvo.msgs[i].re[i]._id
DirectConvo.msgs[i].re[i].profile.prefs.fullname
DirectConvo.msgs[i].timestamp
DirectConvo.msgs[i].attachments
DirectConvo.msgs[i].tags
```

## mailbox.inbox.view
`
url: '/{id}',
templateUrl: 'views/mail_detail.html',
controller: DirectMsgViewCtrl
`

```
DirectConvo.msgs[i].from._id
DirectConvo.msgs[i].to[i].value._id
DirectConvo._id
DirectConvo.msgs
DirectConvo.msgs[i].from.profile.prefs.fullname
DirectConvo.msgs[i].subject
DirectConvo.msgs[i].text
DirectConvo.msgs[i].re
DirectConvo.msgs[i].re.length
DirectConvo.msgs[i].re[i]._id
DirectConvo.msgs[i].re[i].profile.prefs.fullname
DirectConvo.msgs[i].timestamp
DirectConvo.msgs[i].attachments
DirectConvo.msgs[i].tags
```

## mailbox.sent.home
`
url: '',
templateUrl: 'views/mail_list.html',
controller: DirectMsgInboxCtrl
`

```
DirectConvo._id
DirectConvo.msgs.length
DirectConvo.msgs[i]
DirectConvo.msgs[i].from
DirectConvo.msgs[i].from._id
DirectConvo.msgs[i].from.profile.prefs.fullname
DirectConvo.msgs[i].re[i]._id
DirectConvo.msgs[i].re[i].fullname
DirectConvo.msgs[i].subject
DirectConvo.msgs[i].text
DirectConvo.msgs[i].timestamp
DirectConvo.msgs[i].reads
DirectConvo.msgs[i].attachments
```

## mailbox.sent.view
`
url: '/{id}',
templateUrl: 'views/mail_detail.html',
controller: DirectMsgViewCtrl
`

```
DirectConvo.msgs[i].from._id
DirectConvo.msgs[i].to[i].value._id
DirectConvo._id
DirectConvo.msgs
DirectConvo.msgs[i].from.profile.prefs.fullname
DirectConvo.msgs[i].subject
DirectConvo.msgs[i].text
DirectConvo.msgs[i].re
DirectConvo.msgs[i].re.length
DirectConvo.msgs[i].re[i]._id
DirectConvo.msgs[i].re[i].profile.prefs.fullname
DirectConvo.msgs[i].timestamp
DirectConvo.msgs[i].attachments
DirectConvo.msgs[i].tags
```

## mailbox.archive.home
`
url: '',
templateUrl: 'views/mail_list.html',
controller: DirectMsgInboxCtrl
`

```
DirectConvo._id
DirectConvo.msgs.length
DirectConvo.msgs[i]
DirectConvo.msgs[i].from
DirectConvo.msgs[i].from._id
DirectConvo.msgs[i].from.profile.prefs.fullname
DirectConvo.msgs[i].re[i]._id
DirectConvo.msgs[i].re[i].fullname
DirectConvo.msgs[i].subject
DirectConvo.msgs[i].text
DirectConvo.msgs[i].timestamp
DirectConvo.msgs[i].reads
DirectConvo.msgs[i].attachments
```

## mailbox.archive.view
`
url: '/{id}',
templateUrl: 'views/mail_detail.html',
controller: DirectMsgViewCtrl
`

```
DirectConvo.msgs[i].from._id
DirectConvo.msgs[i].to[i].value._id
DirectConvo._id
DirectConvo.msgs
DirectConvo.msgs[i].from.profile.prefs.fullname
DirectConvo.msgs[i].subject
DirectConvo.msgs[i].text
DirectConvo.msgs[i].re
DirectConvo.msgs[i].re.length
DirectConvo.msgs[i].re[i]._id
DirectConvo.msgs[i].re[i].profile.prefs.fullname
DirectConvo.msgs[i].timestamp
DirectConvo.msgs[i].attachments
DirectConvo.msgs[i].tags
```

## mailbox.email_compose

`
url: "/email_compose",
templateUrl: "views/mail_compose.html",
Controller: DirectMsgComposeCtrl
`

```
Person._id
Person.profile.prefs.fullname
DirectConvo.msgs[i].re[i]._id
DirectConvo.msgs[i].re
DirectConvo.msgs[i].subject
DirectConvo.msgs[i].to[i].value._id
DirectConvo.msgs[i].to
DirectConvo.msgs[i].text
DirectConvo.msgs[i].attachments
Person.profile.imageUrl
Person.profile.prefs.fullname
Person._id
```

# Invite

## invite.compose
`
url: "/compose",
templateUrl: "views/referral_compose.html",
Controller: InviteComposeCtrl
`

```
Person._id
Person.profile.imageUrl
Person.profile.prefs.fullname
Person.profile.prefs.email
```

## invite.inbox
`
url: '/inbox',
templateUrl: 'views/invites.html',
Controller: InviteInboxCtrl
`

```
Person.profile.prefs.fullname
// request Schema from personSchema:
request._id
request.source
request.source.profiles.prefs.fullname
request.subject.profile.prefs.fullname
request.timestamp
// membershipRequest Schema from orgSchema:
membershipRequest._id
membershipRequest.org._id
membershipRequest.source.profile.prefs.fullname
membershipRequest.org.profile.prefs.fullname
membershipRequest.source

```
## invite.user
`
url: '/user/{id}',
templateUrl: 'views/invite_view.html',
Controller: InviteViewCtrl
`

```
Person._id
Person.profile.prefs
Person.profile.prefs.fullname
```

## invite.request
`
url: '/request/{id}',
templateUrl: 'views/invite_view.html',
Controller: ThirdPartyInviteViewCtrl
`

```
// request Schema from personSchema:
request._id
request.source.profile.prefs
request.source.profile.prefs.fullname
request.text
request.subject.profile.prefs
request.subject.profile.prefs.fullname
request.timestamp
request.attachments
request.attachments[i].fileId
request.attachments[i].filename
request.attachments[i].timestamp
```

## invite.org
`
url: '/org/{org}/membership-request/{id}',
templateUrl: 'views/membership_request_view.html',
Controller: MembershipRequestViewCtrl
`
```
Org._id
Org.profile.prefs.fullname
// membershipRequest Schema from OrgSchema:
membershipRequest._id
membershipRequest.source.profile.prefs
membershipRequest.source.profile.prefs.fullname
```

# Events

## events.event-list
`
url: "/list",
templateUrl: "views/events-list.html",
Controller: EventListController
`

```
Event.start
Event.timeLeft
Event.subject
Event.topic
Event.description
```


## events.event-book
`
url: "/list",
templateUrl: "views/events-list.html",
Controller: EventListController
`

```
Person.profile.prefs.fullname
// Event being an array of events:
Event.length
Event[i].start
Event[i].end
```

# Network Connections

## network.connections
`
url: "/connections",
templateUrl: "views/connections.html",
Controller: ConnectionsCtrl
`

```
// Person being an array of persons:
Person._id
Person.profile.prefs.fullname
Person.connections.pro.connected.length
Person.connections.patients.connected.length
Person.profile.imageUrl
```

