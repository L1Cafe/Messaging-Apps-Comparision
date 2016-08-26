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

|                  | Skype              | Hangouts           | Telegram           | WhatsApp           | Viber              | Tox                | Signal             |  
| :--------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: |  
| :heart:          | 2128               | 813                | 637                | 431                | 246                | 214                | 155                |  
| Country          | USA                | USA                | Russia             | USA                | Japan              | :question:         | USA                |
| Free (No cost)   | :o:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :o:                | :heavy_check_mark: | :heavy_check_mark: |
| Open source      | :x:                | :x:                | Client only        | :x:                | :x:                | :heavy_check_mark: | :heavy_check_mark: |  
| E2EE chat        | :x:                | :x:                | :o:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |  
| Audio/video      | :heavy_check_mark: | :heavy_check_mark: | :x:                | Audio only         | Audio only         | :heavy_check_mark: | Audio only         |  
| E2EE video/audio | :x:                | :x:                | :x:                | Audio only         | :x:                | :heavy_check_mark: | Audio only         |  
| Audited          | :x:                | :o:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x:                | :heavy_check_mark: |  
| Cross-platform   | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :o:                | :heavy_check_mark: | :heavy_check_mark: | :o:                |  
| Network model    | Centralised        | Centralised        | Centralised        | Centralised        | Centralised        | Peer-to-peer       | Centralised        |  

|                  | Fb Messenger       | LINE               | iMessage           | Threema            | Wire               | Vector             | 
| :--------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | 
| :heart:          | 130                | 76                 | 34                 | 30                 | 22                 | 17                 |
| Country          | USA                | Japan              | USA                | Switzerland        | Switzerland        | :question:         |
| Free (no cost)   | :heavy_check_mark: | :o:                | :o:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | 
| Open source      | :x:                | :x:                | :x:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | 
| E2EE chat        | :o:                | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | 
| Audio/video      | :heavy_check_mark: | Audio only         | :x:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | 
| E2EE audio/video | :o:                | :o:                | :x:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | 
| Audited          | :x:                | :o:                | :heavy_check_mark: | :heavy_check_mark: | :o:                | :x:                |
| Cross-platform   | :heavy_check_mark: | :heavy_check_mark: | :o:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | 
| Network model    | Centralised        | Centralised        | Centralised        | Centralised        | Centralised        | Federated          | 

|                  | Peerio             | 
| :--------------: | :----------------: | 
| :heart:          | 2                  | 
| Country          | USA                | 
| Free (no cost)   | Freemium           | 
| Open source      | Client only        | 
| E2EE chat        | :heavy_check_mark: | 
| Audio/video      | :x:                | 
| E2EE audio/video | :x:                | 
| Audited          | :heavy_check_mark: | 
| Cross-platform   | :heavy_check_mark: |
| Network model    | Centralised        | 

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
