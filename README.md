# Patches
Auto-generated patched for the game

---

[Download](https://github.com/Yejdhi/Patches/releases/download/PatcherApp/PatcherApp_1.1.apk)

---

`com/googleplay/licensing/ServerManagedPolicy`

```smali
...

.method public allowAccess()Z
    .registers 9

    .prologue
    const/4 v3, 0x1

    #const/4 v2, 0x0
    const/4 v2, 0x1

    .line 265
    invoke-static {}, Ljava/lang/System;->currentTimeMillis()J

...

```