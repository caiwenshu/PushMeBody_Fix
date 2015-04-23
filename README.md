# PushMeBody_Fix
对于https://github.com/stefanhafeneger/PushMeBaby的bug fix



    in Xcode5
      You need to replace one line in ioSoch.h:

      #include <CoreServices/../Frameworks/CarbonCore.framework/Headers/MacTypes.h>
      to
        #include <MacTypes.h>
