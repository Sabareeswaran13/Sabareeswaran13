The game mode is REVERSE: You do not have access to the statement. You have to guess what to do by observing the following set of tests:
01 Test 1
Input
Expected output
6
                   _..
  /}_{\           /.-'
 ( o o )-.___...-'/
 ==._.==         ;
      \ i _..._ /,
      {_;/   {_//
                   _..
  /}_{\           /.-'
 ( x x )-.___...-'/
 ==._.==         ;
      \ i _..._ /,
      {_;/   {_//
02 Test 2
Input
Expected output
12
             (`,---.')  (\
              (o,_,o)    ))
             -=>_Y_<=- _,;'
               /`"'\.-'.'
             .'     `<'
             | ;   ; |
             |`,   , |
              \ ;`; /
               ||,||
              /|| ||\
             (,|( )|,)
              (,,Y,,)
             (`,---.')  (\
              (x,_,x)    ))
             -=>_Y_<=- _,;'
               /`"'\.-'.'
             .'     `<'
             | ;   ; |
             |`,   , |
              \ ;`; /
               ||,||
              /|| ||\
             (,|( )|,)
              (,,Y,,)
03 Test 3
Input
Expected output
7
      /\_/\
 /\  / o o \
//\\ \~(*)~/
`  \/   ^ /
   | \|| ||
   \ '|| ||
    \)()-())
      /\_/\
 /\  / x x \
//\\ \~(*)~/
`  \/   ^ /
   | \|| ||
   \ '|| ||
    \)()-())
04 Test 4
Input
Expected output
7
    /\_____/\
   /  o   o  \
  ( ==  ^  == )
   )         (
  (           )
 ( (  )   (  ) )
(__(__)___(__)__)
    /\_____/\
   /  x   x  \
  ( ==  ^  == )
   )         (
  (           )
 ( (  )   (  ) )
(__(__)___(__)__)
05 Test 5
Input
Expected output
11
 /\     /\
{  `---'  }
{  o   o  }
~~>  V  <~~
 \  \|/  /
  `-----'____
  /     \    \_
 {       }\  )_\_   _
 |  \_/  |/ /  \_\_/ )
  \__/  /(_/     \__/
    (__/
 /\     /\
{  `---'  }
{  x   x  }
~~>  V  <~~
 \  \|/  /
  `-----'____
  /     \    \_
 {       }\  )_\_   _
 |  \_/  |/ /  \_\_/ )
  \__/  /(_/     \__/
    (__/
import sys
import math
n = int(input())
for i in range(n):
    row = input()
    p=row.replace("o","x")
    print(p)
