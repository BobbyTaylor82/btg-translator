# btg-translator
This application was inspired after a conversation with an old friend. He informed me he was going on an adventure with his family to Portugal for five weeks. Even though, there are many language translating applications on the interwebs. I thought this would be an excellent opportunity to provide him with a web application that would help him communicate with the locals or even read the newspaper. 

Try it out for yourself.  https://btg-translator.herokuapp.com

![](photo.png)


//MAKEPDS  JOB ...
//STEP1    EXEC PGM=IEFBR14
//SYSUT1   DD DSN=#532.FILE.PDS,DISP=(NEW,CATLG,DELETE),
//            SPACE=(TRK,(1,1),RLSE),
//            UNIT=SYSDA
//SYSUT2   DD DSN=#523.FILE2.PDS,DISP=OLD
//SYSPRINT DD SYSOUT=A
