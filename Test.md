| depth | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| F1 score | 0.335 | 0.493 | 0.517 | 0.507 | 0.438 | 0.501 | 0.000 | 0.000 |
| avg tokens | 3.02 | 110.43 | 277.07 | 568.02 | 1053.03 | 1743.32 | 00.00 | 00.00 |

| branch | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| F1 score | 0.440 | 0.496 | 0.561 | 0.564 | 0.555 | 0.488 |	0.532 | 0.533 |
| avg tokens | 16.16 | 106.78 | 413.28 | 568.02 | 503.44 | 590.92 | 695.64 | 701.92 |

Context: at t=0 Mary got the milk there.at t=1 John moved to the bedroom.at t=2 Sandra went back to the kitchen.at t=3 Mary travelled to the hallway.at t=4 Mary journeyed to the kitchen.
| bAbI-task | task-1 | task-2 | task-3 |
| ------ | ------ | ------ | ------ |
| question | Where is Mary? | Where is milk? | Where was the milk before the kitchen? |
| format | A(Where is Mary?) | A(Who took milk?)+B(Where is the person?) | A(Who took milk?)+B(When did the person get to kitchen?)+C(Where was the person before that time?) |

| bAbI-task | task-1 | task-2 | task-3 |
| ------ | ------ | ------ | ------ |
| Acc(CoT) | 0.607 | 0.467 | 0.281 |
