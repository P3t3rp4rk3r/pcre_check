# pcre_check
Used for the development and testing of PCRE's across suspected malicious URL's for identification.

Blog post - [31MAY2017 - Writing PCRE's for applied passive network defense](http://ropgadget.com/posts/defensive_pcres.html)

Below is the final list of Emotet download PCRE's created in the blog.

```
^http:\/\/([^\x2F]+\/)+[a-zA-Z]{1,3}[0-9]{1}[a-zA-Z]{1,3}-[a-zA-Z]{1,2}[0-9]{2,3}-[a-zA-Z]{1,5}\/$	karttoon 31MAY2017 - Emotet download - [ t5wx-x064-mzdb ]
^http:\/\/([^\x2F]+\/)+(INVOICE|ORDER|CUST|Invoice|Cust)-[0-9]{6,7}-[0-9]{4,5}\/$	karttoon 31MAY2017 - Emotet download - [ INVOICE-864339-98261 ]
^http:\/\/([^\x2F]+\/)+dhl\/paket\/com\/pkp\/appmanager\/[0-9]{10}\/$	karttoon 31MAY2017 - Emotet download - [ dhl/paket/com/pkp/appmanager/8376315127 ]
^http:\/\/([^\x2F]+\/)+[A-Z]{2,3}-[0-9]{8}\.dokument\/$	karttoon 31MAY2017 - Emotet download - [ RRT-13279129.dokument ]
^http:\/\/([^\x2F]+\/)+[A-Z]{2,5}(-[0-9]{2})?-[0-9]{5,10}-(document|doc)-May-[0-9]{2}-2017\/$	karttoon 31MAY2017 - Emotet download - [ EDHFR-08-77623-document-May-04-2017 ]
^http:\/\/([^\x2F]+\/)+download[0-9]{4}\/$	karttoon 31MAY2017 - Emotet download - [ download2467 ]
^http:\/\/([^\x2F]+\/)+[a-zA-Z0-9]{1,4}[0-9]{3}[a-zA-Z]{1,5}[0-9]{3}-[a-zA-Z]{1,3}\/$	karttoon 31MAY2017 - Emotet download - [ LUqc663BAyN333-HoO ]
^http:\/\/([^\x2F]+\/)+[A-Z]{4,5}-[A-Z]{1,4}-[0-9]{5}-DE\/$	karttoon 31MAY2017 - Emotet download - [ NUDA-X-52454-DE ]
^http:\/\/([^\x2F]+\/)+(CUST|ORDER|Cust|Rech|Rechnung)(.)?(-Document)?-[A-Z]{1,4}-[0-9]{2,3}-[A-Z]{1,3}[0-9]{4,6}\/$	karttoon 31MAY2017 - Emotet download - [ CUST.-Document-YDI-04-GQ389557 ]
^http:\/\/([^\x2F]+\/)+[a-z0-9]{1,5}-[a-z0-9]{2,4}(-[a-z0-9]{4,5})?-[a-z]{1,4}\.(view|doc)\/$	karttoon 31MAY2017 - Emotet download - [ zp3x-r88-wuh.view ]
^http:\/\/([^\x2F]+\/)+dhl___status___[0-9]{10}\/$	karttoon 31MAY2017 - Emotet download - [ dhl___status___2668292851 ]
^http:\/\/([^\x2F]+\/)+(ORDER|Rech|CUST|Cust|gescanntes|Scan)(.)?(-Document|-Dokument)?-[0-9]{10,11}\/$	karttoon 31MAY2017 - Emotet download - [ ORDER.-5883789520 ]
^http:\/\/([^\x2F]+\/)+SCANNED\/[A-Z]{2,3}[0-9]{4}[A-Z]{6,9}\/$	karttoon 31MAY2017 - Emotet download [ SCANNED/RZ7498WEXEZB ]
```
