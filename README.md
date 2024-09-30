# data-race-test

> [!NOTE] 
> 
> This is yet another fork of the project [data-race-test](https://code.google.com/archive/p/data-race-test/) \(Thread Sanitizer\).
> 
> The goal of the fork: tried to save documents and [Wiki](https://github.com/derskythe/data-race-test/wiki), which are missing from others<br />
> WIP

![image](https://github.com/user-attachments/assets/db191fa3-1669-424d-a3f6-c20fce3a84b2)

## Description

Race detection tools and more

This page is about **ThreadSanitizer** version 1. <br />
For the new (and better supported) version go to [http://code.google.com/p/thread-sanitizer](https://github.com/google/sanitizers)

This project is about detecting data races (race conditions).<br />
If you are interested in this subject, start browsing wiki pages:

  * ThreadSanitizer — a data race detector
  * DynamicAnnotations — a race detector API
  * RacecheckUnittest — the set of unit tests
  * RaceCheckerClass and RaceVerifier — utilities to check if there is indeed a race
  * ThreadSanitizerAndVim — How to analyze Helgrind or ThreadSanitizer logs using Vim
  * HowToContribute — Read here if you want to help us.

_Contacts:_ **data-race-test(#)googlegroups.com**

## Original `readme.txt` from a parent upstream

This project aims to create a test suite for helgrind 
(a data race detection tool, part of valgrind, http://www.valgrind.org)
and potentially any other data race detector.

Hopefully, everything really useful from this project will 
eventually be merged into the `official` helgrind.

For details, see http://code.google.com/p/data-race-test 

