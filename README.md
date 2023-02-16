# NOTAM Capstone Project

## Questions to ask

* How can I break this problem down into smaller chunks?
* What is the most simple thing I can solve?
* How am I tracking the problems/questions/unknowns I am encountering?
* What are the edge cases?
* How can I show that the algorithm that I'm implementing is "correct"?
* How can I test iterations of the algorithm to know that one is better than another?
* How do I know I have good data?

## Sample routes

Try these departure/destination pairs to see how your algorithm handles them.

KOUN KSWO

KOUN KLAW

KLAX KJFK

KEYW BRW

1K4 1K5

KEYW BRW


## Sample NOTAM dataset

See the `samples` directory for some sample flights that include NOTAMs.

## Using Sample NOTAMs

If you use some of the NOTAMs below to test, you may want to alter a few things:

```
!ORD 12/920 ORD RWY 10L/28R E 300FT WIP UNGROOVED 2212131427-2304302359
            ^^^                                   ^^^^^^^^^^^^^^^^^^^^^
            [1]                                            [2]
```
[1] The NOTAM might have a different airport code. You may want to alter this
to fit one of your departure/destination/enroute airports.

[2] The NOTAM has a date that it is effective. You may want to alter this time
so that it is no longer expired.

## Important NOTAMs to test

Insert these into your testing data to see how they rank!

```
!RNO 01/242 N86 RWY 17/35 CLSD 2301311809-PERM
```
