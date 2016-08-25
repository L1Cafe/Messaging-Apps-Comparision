# Messaging Apps Comparision
A quick reference comparing different messaging apps and their features.
We're only listing protocols and their official implementation. For example, not multiprotocol messengers like Pidgin or Trillian which have many more variables to be taken into account.

## Legend
:o: = not enough data, undisclosed, unknown  
:x: = no, zero  
:question: = optional, incomplete, medium, limited  
:heavy_check_mark: = yes, high, full

:heart: = [AlternativeTo](https://alternativeto.net/) likes  
E2EE = End-To-End Encrypted

|                  | Skype              | Hangouts           | Telegram           | WhatsApp           | Viber              | Tox                | Signal             |  
| :--------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: |  
| :heart:          | 2128               | 813                | 637                | 431                | 246                | 214                | 155                |  
| Country          | USA                | USA                | Russia             | USA                | Japan              | :o:                | USA                |
| Free (No cost)   | :question:         | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :question:         | :heavy_check_mark: | :heavy_check_mark: |
| Open source      | :x:                | :x:                | Client only        | :x:                | :x:                | :heavy_check_mark: | :heavy_check_mark: |  
| E2EE text        | :x:                | :x:                | :question:         | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |  
| Audio/video      | :heavy_check_mark: | :heavy_check_mark: | :x:                | Audio only         | Audio only         | :heavy_check_mark: | Audio only         |  
| E2EE video/audio | :x:                | :x:                | :x:                | Audio only         | :x:                | :heavy_check_mark: | Audio only         |  
| Audited          | :x:                | :question:         | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x:                | :heavy_check_mark: |  
| Cross-platform   | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :question:         | :heavy_check_mark: | :heavy_check_mark: | :question:         |  
| Network model    | Centralised        | Centralised        | Centralised        | Centralised        | Centralised        | Peer-to-peer       | Centralised        |  

|                  | Fb Messenger       | LINE               | iMessage           | Threema            | Wire               | Vector             | 
| :--------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | :----------------: | 
| :heart:          | 130                | 76                 | 34                 | 30                 | 22                 | 17                 |
| Country          | USA                | Japan              | USA                | Switzerland        | Switzerland        | :o:                |
| Free (no cost)   | :heavy_check_mark: | :question:         | :question:         | :x:                | :heavy_check_mark: | :heavy_check_mark: | 
| Open source      | :x:                | :x:                | :x:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | 
| E2EE text        | :question:         | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | 
| Audio/video      | :heavy_check_mark: | Audio only         | :x:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | 
| E2EE audio/video | :question:         | :o:                | :x:                | :x:                | :heavy_check_mark: | :heavy_check_mark: | 
| Audited          | :x:                | :question:         | :heavy_check_mark: | :heavy_check_mark: | :o:                | :x:                |
| Cross-platform   | :heavy_check_mark: | :heavy_check_mark: | :question:         | :x:                | :heavy_check_mark: | :heavy_check_mark: | 
| Network model    | Centralised        | Centralised        | Centralised        | Centralised        | Centralised        | Federated          | 

|                  | Peerio             | 
| :--------------: | :----------------: | 
| :heart:          | 2                  | 
| Country          | USA                | 
| Free (no cost)   | Freemium           | 
| Open source      | Client only        | 
| E2EE text        | :heavy_check_mark: | 
| Audio/video      | :x:                | 
| E2EE audio/video | :x:                | 
| Audited          | :heavy_check_mark: | 
| Cross-platform   | heavy_check_mark   | 
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
