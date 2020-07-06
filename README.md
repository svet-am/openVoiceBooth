# openVoiceBooth
An Open Source Client/Server Voice-Over Recording Environment

# Goals and Overview
## Technical Goals
Be multi-platform (Windows, Mac, Linux)
Appear as a standard audio device to the host OS (for input/output)
Use IEEE-1588 for TSN
Support direct Client/Server or ensemble client/server application
Support video as a sideband (optional & opportunisitic) channel
Support OS-native audio interfaces (JACK, ASIO, DirectSound, WASAPI, CoreAudio)

## Operational Goals
Be similar in application to ISDN for talent and studio engineer
Support talkback functionality for sessions
Support a private “phone book” of contacts for both talent and studios
Support an open/public contact repository
Support multiple modes of uncompressed content transfer - immediate (attempt to send uncompressed at the same time as recording), deferred (cache uncompressed content and send at a later time), opportunistic (cache uncompressed content and send automatically later in the session when bandwidth allows)
