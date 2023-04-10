# Tips and tricks by xnucrack team

# Table of Contents
* [General](#general)
    + [Modifying contents of .app](#modifying-contents-of-app)

## General

### Modifying contents of .app

In the situations where you would like to modify the content of some application but the SIP gets in your way. Just copy app from `/Applications` to somewhere else, modify it there, codesign and replace old version of an app with the new one.  
This can be useful with `Electron` apps where you would like to quickly modify source files.