---
title: Installing Live Edit Silently
review:
    comment: ''
    date: ''
    status: ok
labels:
    - live-edit
confluence:
    ajs-parent-page-id: '16809994'
    ajs-parent-page-title: Installing and Setting up Related Software
    ajs-space-key: ADMINDOC58
    ajs-space-name: Nuxeo Installation and Administration - 5.8
    canonical: Installing+Live+Edit+Silently
    canonical_source: 'https://doc.nuxeo.com/display/ADMINDOC58/Installing+Live+Edit+Silently'
    page_id: '16810052'
    shortlink: RIAAAQ
    shortlink_source: 'https://doc.nuxeo.com/x/RIAAAQ'
    source_link: /display/ADMINDOC58/Installing+Live+Edit+Silently
history:
    - 
        author: Solen Guitter
        date: '2016-08-30 13:45'
        message: ''
        version: '3'
    - 
        author: Solen Guitter
        date: '2013-09-18 15:10'
        message: ''
        version: '2'
    - 
        author: Arnaud Kervern
        date: '2013-09-18 15:03'
        message: ''
        version: '1'

---
To install MSOffice Live Edit in silent mode, without any user interaction:

```powershell
msiexec /i nuxeo-liveedit-msoffice.msi APPLICATIONFOLDER="c:/your/install/path" /qn
```

<div class="row" data-equalizer data-equalize-on="medium"><div class="column medium-6">{{#> panel heading='More Live Edit Admin Documentation'}}

*   [Configuring a Reverse Proxy to Work with Live Edit and Client Certificate Authentication]({{page page='configuring-a-reverse-proxy-to-work-with-live-edit-and-client-certificate-authentication'}})
*   [Configuration Examples]({{page page='configuration-examples'}})

{{/panel}}</div><div class="column medium-6">{{#> panel heading='Other Live Edit Related Documentation'}}

*   [Live Edit Compatibility Table]({{page space='userdoc58' page='live-edit-compatibility-table'}})
*   [Working with Live Edit]({{page space='userdoc58' page='working-with-live-edit'}})

{{/panel}}</div></div>