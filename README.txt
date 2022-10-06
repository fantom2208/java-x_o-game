purpose:
        java application game TicTacToe (crosses and zeros)

engine: openjdk version 11.0.16
        OpenJDK Runtime Environment (build 11.0.16+8-post-Ubuntu-0ubuntu118.04)
        OpenJDK 64-Bit Server VM (build 11.0.16+8-post-Ubuntu-0ubuntu118.04, mixed mode, sharing)

initialization (first time):
        tbd

running (all times):
        tbd

features:
        0) field size fixed by default 3x3
        1) algorithm to define winnwers checks only for rows or columns
        (daigonals to be added later)
        2) algorithm to define winnwers developed in common way for field size

known issues:
        0) in case of gradle issue
           "Could not fetch model of type 'BuildEnvironment' using connection to Gradle distribution"
        open
            gradle/wrapper/gradle-wrapper.properties
        and set a proper distributionUrl there:
            distributionUrl=https\://services.gradle.org/distributions/gradle-4.8.1-all.zip

        1) no algorithm to check if game finished ("x" or "o" win or 'tie') for diagonals
           solution: define new function with loops
           when: next step
        2) windows shape is not scallable and not fit to small screens
           solution: define how to change dimension of window
           when: tbd
        3) for 2 players function checkGameWinner() calls twice for 1 change
           for 1 player onece for 1 change. Not critical, but need to find reason


git remote:
        github: tbd




java environment list:
------------------------------------------------------------------------------
tbd