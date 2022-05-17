# luca.lk

Private Profile/Contact page featuring important information without the clutter of my main home page ( https://luca-kiebel.de )

The files are:
 - `_redirects` file is for cloudflare pages redirects, features links to my socials

 - `id` is my public SSH Key, mostly for setting up server access easier ( `curl -L luca.lk/id >> ~/.ssh/authorized_keys` )

 - `ids` is a script wrapper around the command from above, so running `curl -L luca.lk/ids | bash` will do the same as `curl -L luca.lk/id >> ~/.ssh/authorized_keys`

 - `lucakiebel.vcf` is a vCard of my contact information, this can be used for smaller QR codes with my information as a contact in it ( accessible via `/vcard` or `/v` )

 - `work.vcf` same as `lucakiebel.vcf` but for my other job at [@adessoSE](https://github.com/adessoSE) ( accessible via `/w` )
