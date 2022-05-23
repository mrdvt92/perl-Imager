# perl-Imager
perl-Imager.spec file to get https://metacpan.org/dist/Imager running on RedHat 7 without GIF and T1 requirements

## Hack but works

This is a hack job but it works for my RedHat 7 system.  If I knew how to better tweak the process, I would target remove the GIF and T1 parts that are not supported on RedHat 7.

## To build

Ensure that giflib-devel and t1lib-devel are NOT installed.  I build on CentOS 7 and push to RedHat 7 so this is really only a concern for those of us who have crazy environments.


