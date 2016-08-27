# Messaging Apps Comparision
A quick reference comparing different messaging apps and their features.
We're only listing protocols and their official implementation. For example, not multiprotocol messengers like Pidgin or Trillian which have many more variables to be taken into account.

## Legend
:question: = not enough data, undisclosed, unknown  
:x: = no, zero  
:o: = optional, incomplete, medium, limited  
:heavy_check_mark: = yes, high, full

:heart: = [AlternativeTo](https://alternativeto.net/) likes  
E2EE = End-To-End Encrypted

|                  | Skype              | Hangouts           | Telegram           | WhatsApp           | Viber              | Tox                | Signal             | Fb Messenger       | LINE               | iMessage           | Threema            | Wire               | Vector             | Peerio             |                  |
| :--------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :--------------: |
| :heart:          | 2128               | 813                | 637                | 431                | 246                | 214                | 155                | 130                | 76                 | 34                 | 30                 | 22                 | 17                 | 2                  | :heart:          |
| Country          | USA                | USA                | Russia             | USA                | Japan              | :question:         | USA                | USA                | Japan              | USA                | Switzerland        | Switzerland        | :question:         | USA                | Country          |
| Free (No cost)   | :o:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :o:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :o:                | :o:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | Freemium           | Free (no cost)   |
| Open source      | :x:                | :x:                | Client only        | :x:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | :x:                | :x:                | :x:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | Client only        | Open source      |
| E2EE chat        | :x:                | :x:                | :o:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :o:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | E2EE chat        |
| Audio/video chat | :heavy_check_mark: | :heavy_check_mark: | :x:                | Audio only         | Audio only         | :heavy_check_mark: | Audio only         | :heavy_check_mark: | Audio only         | :x:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | :x:                | Audio/video chat |
| E2EE video/audio | :x:                | :x:                | :x:                | Audio only         | :x:                | :heavy_check_mark: | Audio only         | :o:                | :o:                | :x:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | :x:                | E2EE audio/video |
| Audited          | :x:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x:                | :heavy_check_mark: | :x:                | :o:                | :heavy_check_mark: | :heavy_check_mark: | :o:                | :x:                | :heavy_check_mark: | Audited          |
| Cross-platform   | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :o:                | :heavy_check_mark: | :heavy_check_mark: | :o:                | :heavy_check_mark: | :heavy_check_mark: | :o:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | Cross-platform   |
| Network model    | Centralised        | Centralised        | Centralised        | Centralised        | Centralised        | Peer-to-peer       | Centralised        | Centralised        | Centralised        | Centralised        | Centralised        | Centralised        | Federated          | Centralised        | Network model    |

### Template:
```
Name               |
:----------------: |
Likes              |
Country            |
Pricing            |
Source             |
E2EE               |
AV                 |
E2EE AV            |
Audited            |
Cross-platform     |
NM                 |
```

### Missing apps:
- Conversations (XMPP client)
- Google Allo
- Cryptocat
- Slack
- HipChat
- Wickr

### TODO:
- Plausible deniability
- Forward secrecy
- Contact verification
- Message auto-destruction
- Threat level (suspicion? PRISM? criticisms?)
- Does it require e-mail, phone number, real name, Google, Facebook account, etc?
- Two Factor Auth
- Stickers, GIFs
- Bot API
- Extra features (channels? customizable usernames?)
- Privacy: Can you hide last seen?
