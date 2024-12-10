# zookeper

- [zookeper](#zookeper)
  - [learning](#learning)
  - [about](#about)
  - [stages](#stages)
    - [1: rush into print](#1-rush-into-print)
    - [2: show me an animal](#2-show-me-an-animal)
    - [3: whats inside](#3-whats-inside)

## learning
this project is aimed at our beginners. it helps you understand some syntax basics and learn how to work with variables, data storage types such as lists, and while loops.

## about
this short code challenge can help the local zoo look after its denizens. you will create a tool for monitoring animals and their status.

## stages
### 1: rush into print
<details>
<summary>first, let's try to get some simple output from your code</summary>

#### 1.1 description
there are many animals in the zoo, and all of them need care. the animals must be fed, cleaned, surrounded by their kin, and kept happy. that is a difficult task for our large zoo, so one of your employers has suggested a more convenient way to keep track of everything. she wants to be able to pull up a video feed of any animal in the zoo with the help of a program. being able to check on each habitat would help the zookeepers take care of our furry friends more efficiently!

in this project, you will create a program that helps the zookeepers check on the animals and make sure that they're doing well. your product will be able to process commands from the zookeepers and display the animals on a monitor.

#### 1.2 objectives
to begin with, you will develop a simple printer. your program should display the text from the output example.

#### 1.3 examples
the output:
```
i love animals!
let's check on the animals...
the deer looks fine.
the bat looks happy.
the lion looks healthy.
```

</details>

### 2: show me an animal
<details>
<summary>show the zookeeper an image of her ward</summary>

#### 2.1 description
one of the most important parts of working with animals is keeping an eye on them. we need to see the animals on the screen to know how they are doing, right? now we are ready to print something awesome: an image of an animal!

#### 2.2 objectives
for the second stage, you will need to develop an animal printer. your program should display the animal identified in the code field.

#### 2.3 examples
your output should contain the following ascii image:

```
switching on the camera in the camel habitat...
 ___.-''''-.
/___  @    |
',,,,.     |         _.'''''''._
     '     |        /           \
     |     \    _.-'             \
     |      '.-'                  '-.
     |                               ',
     |                                '',
      ',,-,                           ':;
           ',,| ;,,                 ,' ;;
              ! ; !'',,,',',,,,'!  ;   ;:
             : ;  ! !       ! ! ;  ;   :;
             ; ;   ! !      ! !  ; ;   ;,
            ; ;    ! !     ! !   ; ;
            ; ;    ! !    ! !     ; ;
           ;,,      !,!   !,!     ;,;
           /_I      L_I   L_I     /_I
look at that! our little camel is sunbathing!
```

</details>

### 3: whats inside
<details>
<summary>the zookeeper wants to know what is inside each habitat, by its number.</summary>

#### 3.1 description
the third stage requires you to increase the capabilities of your software. now it should be able to recognize the number of a specific habitat from the input and show the animals living there.

add all of the variables from the template to a single variable with the list type. the order of variables matters: they must appear on the list in the order in which they're defined in the code. the list must contain all of the variables with no duplicates.

#### 3.2 objectives
in this stage your program should:

1. ask for the number of the desired habitat using the following phrase: `please enter the number of the habitat you would like to view:`
2. use the input number as an index of your habitats to print its content.
3. end with the following phrase:

```
---
you've reached the end of the program. to check another habitat, please restart the watcher.
```

#### 3.3 examples
the greater-than symbol followed by a space (`> `) represents the user input. notice that it's not part of the input.

example 1
```
please enter the number of the habitat you would like to view: > 5

switching on the camera in the rabbit habitat...
         ,
        /|      __
       / |   ,-~ /
      Y :|  //  /
      | jj /( .^
      >-"~"-v"
     /       Y
    jo  o    |
   ( ~T~     j
    >._-' _./
   /   "~"  |
  Y     _,  |
 /| ;-"~ _  l
/ l/ ,-"~    \
\//\/      .- \
 Y        /    Y
 l       I     !
 ]\      _\    /"\
(" ~----( ~   Y.  )
It looks like we will soon have more rabbits!
---
you've reached the end of the program. to check another habitat, please restart the watcher.
```

example 2
```
please enter the number of the habitat you would like to view: > 4

switching on the camera in the bat habitat...
_________________               _________________
 ~-.              \  |\___/|  /              .-~
     ~-.           \ / o o \ /           .-~
        >           \\  W  //           <
       /             /~---~\             \
      /_            |       |            _\
         ~-.        |       |        .-~
            ;        \     /        i
           /___      /\   /\      ___\
                ~-. /  \_/  \ .-~
                   V         V
This bat looks like it's doing fine.
---
you've reached the end of the program. to check another habitat, please restart the watcher.
```

</details>

[<<](https://github.com/eucarizan/front-end/blob/main/README.md)
<!--
:%s/\(Sample \(Input\|Output\) \d:\)\n\(.*\)/```\r\r**\1**\r```\3/gc

### 0: 
<details>
<summary></summary>

#### 0.1 description

#### 0.2 objectives

#### 0.3 examples

</details>
-->

