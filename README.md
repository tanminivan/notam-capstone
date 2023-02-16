# NOTAM Capstone Project

## Questions to ask

* How can I break this problem down into smaller chunks?
* What is the simplest thing I can solve?
* What if I compared just two NOTAMs?
* How am I tracking the problems/questions/unknowns I am encountering?
* What are the edge cases?
* How can I show that the algorithm that I'm implementing is "correct"?
* How can I test iterations of the algorithm to know that one is better than another?
* How do I know I have good data?

## Sample routes

Try these departure/destination pairs to see how your algorithm handles them.

KOUN → KSWO

KOUN → KLAW

KLAX → KJFK

KEYW → BRW

1K4 → 1K5

KEYW → BRW

## Sample NOTAM dataset

See the `samples` directory for full-flight sample NOTAMs.

## Using Sample NOTAMs

If you use some of the NOTAMs below to test, you may want to alter a few things:

```
!ORD 12/920 ORD RWY 10L/28R E 300FT WIP UNGROOVED 2212131427-2304302359
            ^^^                                   ^^^^^^^^^^^^^^^^^^^^^
            [1]                                            [2]
```
[1] The NOTAM might have a different airport code. You may want to alter this
to fit one of your departure/destination/enroute airports if you are
considering location in your ranking.

[2] The NOTAM has a date that it is effective. You may want to alter this time
to be expired/unexpired to see how it affects your ranking. There is no need to
consider past NOTAMs.

## NOTAMs worth testing

Insert these into your testing data to see how they rank! I'll be updating
this list as I find more, so watch this space.

```
!RNO 01/242 N86 RWY 17/35 CLSD 2301311809-PERM
```

```
!GOK 02/002 GOK AD AP WILDLIFE HAZARD DEER 2302081859-2304282359
```

```
!DCA 01/324 0V4 AD AP FUEL NOT AVBL 2101211610-PERM
```

```
!GNV 02/086 68J AD AP CLSD 1802091424-PERM
```

```
!VLD 02/015 VLD SVC TWR FREQ 120.9 CHANGED TO 128.35 2302231200-PERM
```

```
!BNA 09/511 JWN COM UNICOM FREQ 122.7 U/S 2109231712-PERM
```

```
!MCN 05/552 IFM NAV VOR U/S 2205241348-PERM
```

```
!VNY 12/033 VNY NAV VOR/DME 301-325 BEYOND 10NM UNUSABLE 2212151422-PERM
```

## References

* [NOTAM Basics for Pilots](https://www.faa.gov/sites/faa.gov/files/about/initiatives/notam/what_is_a_notam/Pilots_NOTAM_primer_for_2021.pdf)
* [Appendix A: NOTAM Examples](https://www.faa.gov/air_traffic/publications/atpubs/notam_html/appendix_a.html)

