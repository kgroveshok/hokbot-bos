This document lists the various language contexts and the syntax that can be used to control the bot,
or for the bot to control other bots.


|Context             |Command                                           |Description                                                           |
|--------------------|--------------------------------------------------|----------------------------------------------------------------------|
|context-born        |                                                  | This context is the entry point for all bots                         |
|context-learning    |                                                  | In this context the bot is preparing to listen to learning commands  |
|context-learning    | listen to me                                     | Begin to learn something                                             |
|context-listen-line | finished                                         | Signal the end of learning something. Goes back to waiting context   |
|context-listen-line | learn line                                       | Learn a new ritual line                                              |
|context-listen-line | learn new performance                            | Start to learn a whole new ritual                                    |
|context-listen-line | learn new ritual                                 | Start to learn a whole new ritual                                    |
|context-listen-line | learn new script                                 | Start to learn a whole new ritual                                    |
|context-listen-line | learn ritual                                     | Learn a new ritual line                                              |
|context-listen-line | learn syntax                                     | Learn new language syntax                                            |
|context-listen-line | remember                                         | Does nothing                                                         |
|context-listen-line | ritual                                           | List out a ritual                                                    |
|context-listen-line | show me ritual                                   | List out a ritual                                                    |
|context-listen-line | tell me ritual                                   | List out a ritual                                                    |
|context-listen-line | what is ritual                                   | List out a ritual                                                    |
|context-waiting     | assign                                           | Set ritual values                                                    |
|context-waiting     | brain auto save off                              | Stop auto save                                                       |
|context-waiting     | brain auto save on                               | Auto save the language structure                                     |
|context-waiting     | brain dump                                       | Display the current language structure                               |
|context-waiting     | brain reset                                      | Remove any saved settings and stop                                   |
|context-waiting     | brain save                                       | Save the current language structure                                  |
|context-waiting     | die                                              | Cause bot to stop                                                    |
|context-waiting     | hello                                            | Say hello                                                            |
|context-waiting     | hi                                               | Say hello                                                            |
|context-waiting     | hokbos                                           | Learn a something from the hokbot-bos git repo instead of learning li|
|context-waiting     | join coven                                       | Assign the coven that this bot will work from                        |
|context-waiting     | list rituals                                     | List out the rituals the bot knows                                   |
|context-waiting     | listen                                           | Trigger learning mode                                                |
|context-waiting     | perform ritual                                   | Start a learned ritual                                               |
|context-waiting     | perform script                                   | Start a learned ritual                                               |
|context-waiting     | perform-ritual                                   | TODO                                                                 |
|context-waiting     | rejoin                                           | Force a rejoin to the coven                                          |
|context-waiting     | ritual                                           | TODO                                                                 |
|context-waiting     | select empowerment                               | Set the engine to use in sigil creation                              |
|context-waiting     | set                                              | Set ritual values                                                    |
|context-waiting     | sigil                                            | Trigger sigil creation                                               |
|context-waiting     | sleep                                            | TODO                                                                 |
|context-waiting     | speach                                           | Enable a physical speach engine if the bot is on hardward such as a R|
|context-waiting     | teach ritual                                     | Ask some to teach the ritual to all present                          |
|context-waiting     | test                                             | Testing                                                              |
|context-waiting     | your colour pallete is                           | TODO                                                                 |
|context-waiting     | your creation method is                          | TODO                                                                 |
|context-waiting     | your encoding method is                          | TODO                                                                 |
|context-waiting     | your gender is                                   | TODO                                                                 |
|context-waiting     | your intent is                                   | Set the intent of the ritual                                         |
|context-waiting     | your role is                                     | Assign a role within the ritual                                      |
|context-waiting     | your secondary creation method is                | TODO                                                                 |
|context-waiting     | your secondary encoding method is                | TODO                                                                 |
|context-waiting     | your secondary intent is                         | TODO                                                                 |
|context-waiting     | your source is                                   | TODO                                                                 |
|context-waiting     | your sub creation method is                      | TODO                                                                 |
|context-waiting     | your sub encoding method is                      | TODO                                                                 |
|context-waiting     | your sub intent is                               | Set any other intents for repeated sigil generations within the ritua|
|context-waiting     | your target is                                   | TODO                                                                 |