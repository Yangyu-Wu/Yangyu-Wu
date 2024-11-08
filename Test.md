| depth | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| F1 score | 33.5 | 49.3 | 51.7 | 56.4 | 43.8 | 50.1 | 51.5 | 49.1 |
| avg tokens | 14.71 | 110.43 | 277.07 | 568.02 | 1053.03 | 1743.32 | 2484.12 | 3645.76 |

| branch | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| F1 score | 44.0 | 49.6 | 56.1 | 56.4 | 55.5 | 48.8 |	53.2 | 53.3 |
| avg tokens | 16.16 | 106.78 | 413.28 | 568.02 | 503.44 | 590.92 | 695.64 | 701.92 |

| method | Direct | CoT | SI | ReAct | Self-Ask | FractR |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| F1 score | 34.3 | 38.5 | 21.5 | 27.9 | 39.0 | 49.2 |
| avg tokens | 14.51 | 49.13 | 827.87 | 276.87 | 64.46 | 590.92 |


Context: at t=0 Mary got the milk there.at t=1 John moved to the bedroom.at t=2 Sandra went back to the kitchen.at t=3 Mary travelled to the hallway.at t=4 Mary journeyed to the kitchen.
| bAbI-task | task-1 | task-2 | task-3 |
| ------ | ------ | ------ | ------ |
| question | Where is Mary? | Where is milk? | Where was the milk before the kitchen? |
| format | A(Where is Mary?) | A(Who took milk?)+B(Where is the person?) | A(Who took milk?)+B(When did the person get to kitchen?)+C(Where was the person before that time?) |

| bAbI-task | task-1 | task-2 | task-3 |
| ------ | ------ | ------ | ------ |
| Acc(CoT) | 60.7 | 46.7 | 28.1 |


