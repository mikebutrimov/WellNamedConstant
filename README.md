# Well Named Constants
As you know, in software development there are two big, fundamental problems yet not resolved:
naming and cache invalidation.
 
We couldn't address both of them at once, so main idea of this library is to focus on naming.
 
Imagine, you have set up new fancy static analyser and first thing, you see in your glorious project is:
 
![Consider defining it to a well named constant](https://i.ibb.co/z6rxKkg/image-2020-04-01-00-41-02.png)
 
Yes, it is good practice to name all constant integers as REAL_TRUE_CONSTANTS, but you know how boring it is.
 
Correction: it was.
 
Now with this revolution library you can have at your disposal all first thousand of perfectly named integers from 0 to 1000.
 
Just imagine how nice your code can be:
 
```kotlin
class enum MyEnum {
    ACCESS_DENIED(WellNamedConstant.THIRTY_EIGHT),
    STOP_DDOS(WellNamedConstant.THIRTY_NINE),
    COMMAND_IS_OFF(WellNamedConstant.FORTY),
    PIDOR_COMPETITION(WellNamedConstant.FORTY_ONE),
    COMPETITION_ONE_MORE_PIDOR(WellNamedConstant.FORTY_TWO),
    HELP_MESSAGE(WellNamedConstant.FORTY_THREE),
    USER_ENTERING_CHAT(WellNamedConstant.FORTY_FOUR)
}
```
 
Isn't it beautiful?
