# BBTransfer
These scripts all use the fact that trying to use a string in the boombox remote event will create a serverwide error containing that string. This can be used to send all sorts of data that the other people using this script will decode and use as instructions to do things like create blocks that both parties can see. 

## Todo list
- [ ] Fix part duplication (causes lag when camera close to parts) , i.e fix new data check
- [ ] More BBBuild tools (custom part size, custom rotation, Model inserter [create several parts at once] )
- [ ] Find a way to encrypt data without using Synapse X functions to maintain compatability
- [ ] Script sharing
  - [ ] make others execute a loadstring
  - [ ] security measures to prevent obvious threats like ip logging
- [ ] Simplify usage (API-esk to allow easy implementation into GUIS etc. )
- [ ] Detect when players in game run script (print authenticator in console?)
