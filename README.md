# st
st is a simple terminal implementation for X (by suckless) [customized]
Original: https://st.suckless.org/

## Patches/Customizations in use
- none
  - nourl

## Keyboard Customizations
none

## Patching process
My patching strategy:
    upstream branch is pulled and in sync with suckless upstream
    dev is the testing version
    master is my normal current running version (live)

to apply a new patch:
    checkout upstream
    branch upstream to newpatch
    apply patch to newpatch name
    commit and push, resolving any conflicts
    checkout dev
    merge newpatch, resolving any conflicts
    push newpatch
    test dev branch for functionality
    merge dev into master
    test master


