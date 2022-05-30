# Carplay AccessorySDK leaked version
## Require:

```
 bison==2.5.1
 Bonjour(mDNSResponder)==567
```

## Build:
rename carplay to CarPlay_Plugin cd CarPlay_Plugin\PlatformPOSIX

```
edit Makefile 
#COMMON_WARNINGS += -Werror COMMONFLAGS += -fPIC
```


Missing mh_carplay.h, requires mfi chip.
