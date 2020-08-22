+++
title = "Code Test"
date = 2020-08-22T10:04:59-05:00
images = []
tags = ["powershell", "another", "foo"]
categories = ["DevOps"]
+++

This is just a placeholder post while I prototype different kinds of posts. This one in particular should show some properly formatted PowerShell code.

```powershell
# this is a comment
function Invoke-MyFunction {
    [CmdletBinding()]
    Param(
        [switch]$Awesome
    )

    if ( $Awesome ) {
        Write-Host "Awesome!"
    } else {
        Write-Host "...whatever..."
    }
}
```

The following paragraph would probably contain some final thoughts and conclusions and possibly some [links to other material](https://powershellgallery.com).
