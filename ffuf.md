# FFUF 

ffuf stands for Fuzz Faster U Fool. It's a tool used for web enumeration, fuzzing, and directory brute forcing.

1. [Basic use](#basic-use)

## [Add Some Word in wordlist](#add-some-word-in-wordlist)

## [Extensions](#extensions)

## [Hide Status Code](#hide-status-code)





## Basic Use

    ffuf -u http://example.com/FUZZ -w wordlist.txt

## Add Some Word in wordlist

    ffuf -u http://example.com/FUZZ -w wordlist.txt:asif

## Extensions

    ffuf -u http://example.com/FUZZ -w wordlist.txt -e .php,.txt,.exe

## Hide Status Code

     ffuf -u http://example.com/FUZZ -w wordlist.txt -fc 403,302
