# fable-import-sp-pnp-js
[Fable](http://fable.io/) bindings for [SharePoint and the SharePoint Framework Patterns and Practices JavaScript Core Library](https://github.com/SharePoint/PnP-JS-Core). 
Simple library that can be used to create client-only SharePoint application in [F#](http://fsharp.org/).

## JavaScript API reference

    open Fable.Import
    let list = pnp.Globals.sp.web.lists.getByTitle("Documents")
    list.breakRoleInheritance()
