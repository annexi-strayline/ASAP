# ASAP
The ANNEXI-STRAYLINE AURA Public Repository

## AURA Configuration for using this repository

Replace _X with the appropriate number for your project.

```ada
package AURA.Respository_X with Pure is
    Format         : constant Repository_Format := git;
    Location       : constant String            := "https://github.com/annexi-strayline/ASAP.git";
    Tracking_Branch: constant String            := "stable-0.1";
end AURA.Repository_X;
```
