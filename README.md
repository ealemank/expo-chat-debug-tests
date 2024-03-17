# expo-chat-debug-tests
small playground repo to figure out rendering problems with react-native-gifted-chat

To run expo:

npx expo start -c

To repro the problem:
- start the web simulation
- npx expo start -c -w
- initial chat messages should show up: 'Hello Developer'
- refresh the page and the 'hello developer' message no longer shows up
