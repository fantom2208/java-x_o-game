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
        0) field size now fixed by default 3x3 (lots of places with value 3)
        1) algorithm to define winnwers developed in common way for field size

known issues:
        0) in case of gradle issue
           "Could not fetch model of type 'BuildEnvironment' using connection to Gradle distribution"
        open
            gradle/wrapper/gradle-wrapper.properties
        and set a proper distributionUrl there:
            distributionUrl=https://services.gradle.org/distributions/gradle-6.1-all.zip

        3) for 2 players function checkGameWinner() calls twice for 1 change
           for 1 player onece for 1 change. Not critical, but need to find reason


git remote:
        github: tbd




java environment list:
------------------------------------------------------------------------------
tbd