# Star-Fighter (Multiplayer version)

Source Code Additions for Multiplayer Functionality:

Classes created in _Star-Fighter\SOURCE\data\scripts\scenes.py_ to make the game multiplayer

**MultiplayerMessage** - Stores message to be sent to client/server

**MultiplayerDataTransferServer** - A class that handles server side operations

**MultiplayerDataTransferClient** - A class that handles client side operations

**MultiplayerOptionsScene** - A class that manages multiplayer options (Client,Server run in Test Mode for example)

**ServerScreenClientConnect** - Manages server screen display before the game starts (waiting for client to connect...etc...)

**ClientScreenServerConnect** - Manages client screen display before the game starts

Further changes to script code:

TitleScene class in handle_events
   - Handle multiplayer or one player selection

_YouTube video below shows running in test mode (localhost) on same machine...._

[![Star-Fighter Multiplayer](https://img.youtube.com/vi/Tqp-eb_XjbI/0.jpg)](https://www.youtube.com/watch?v=Tqp-eb_XjbI)
