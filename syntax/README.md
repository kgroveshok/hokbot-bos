
|Context             |Command                       |Description                                                 |
|--------------------|------------------------------|------------------------------------------------------------|
|context-born        |                              | This context is the entry point for all bots               |
|context-learning    |                              | In this context the bot is preparing to listen to learning |
|context-learning    |   listen     to       me     | Begin to learn something                                   |
|context-listen-line |   finished                   | Signal the end of learning something. Goes back to waiting |
|context-listen-line |   learn     line             | Learn a new ritual line                                    |
|context-listen-line |   learn     new       perform| Start to learn a whole new ritual                          |
|context-listen-line |   learn     new       ritual | Start to learn a whole new ritual                          |
|context-listen-line |   learn     new       script | Start to learn a whole new ritual                          |
|context-listen-line |   learn     ritual           | Learn a new ritual line                                    |
|context-listen-line |   learn     syntax           | Learn new language syntax                                  |
|context-listen-line |   remember                   | Does nothing                                               |
|context-listen-line |   ritual                     | List out a ritual                                          |
|context-listen-line |   show     me       ritual   | List out a ritual                                          |
|context-listen-line |   tell     me       ritual   | List out a ritual                                          |
|context-listen-line |   what     is       ritual   | List out a ritual                                          |
|context-waiting     |   assign                     | Set ritual values                                          |
|context-waiting     |   brain     auto       save  | Stop auto save                                             |
|context-waiting     |   brain     auto       save  | Auto save the language structure                           |
|context-waiting     |   brain     dump             | Display the current language structure                     |
|context-waiting     |   brain     reset            | Remove any saved settings and stop                         |
|context-waiting     |   brain     save             | Save the current language structure                        |
|context-waiting     |   die                        | Cause bot to stop                                          |
|context-waiting     |   hello                      | Say hello                                                  |
|context-waiting     |   hi                         | Say hello                                                  |
|context-waiting     |   hokbos                     | Learn a something from the hokbot-bos git repo instead of l|
|context-waiting     |   join     coven             | Assign the coven that this bot will work from              |
|context-waiting     |   list     rituals           | List out the rituals the bot knows                         |
|context-waiting     |   listen                     | Trigger learning mode                                      |
|context-waiting     |   perform     ritual         | Start a learned ritual                                     |
|context-waiting     |   perform     script         | Start a learned ritual                                     |
|context-waiting     |   rejoin                     | Force a rejoin to the coven                                |
|context-waiting     |   select     empowerment     | Set the engine to use in sigil creation                    |
|context-waiting     |   set                        | Set ritual values                                          |
|context-waiting     |   sigil                      | Trigger sigil creation                                     |
|context-waiting     |   speach                     | Enable a physical speach engine if the bot is on hardward s|
|context-waiting     |   teach     ritual           | Ask some to teach the ritual to all present                |
|context-waiting     |   test                       | Testing                                                    |