<h2>nginx rpm spec file & some nginxtras</h2>

<h3>nginx custom rpm build for CentOS 7</h3>
<p>Pretty straight forward. Installs all nginx items in /etc/nginx<br>
<p>Uses latest pcre, zlib, and openssl<br>
<p>Should work seamlessly on RHEL 7 and Scientific Linux 7.<br>
<p>Big thanks to some old posts at stackoverflow and the EPEL nginx package maintainer Jamie Nguyen.</p>

<p>Quick RPM Build Cheat</p>
```
rpmbuild -ba nginx.spec
```

<h3>Licensing</h3>
<p>The MIT License.  See LICENSE.txt for details</p>

