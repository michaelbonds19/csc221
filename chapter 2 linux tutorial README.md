Activity 1:
/etc - Stores config files for the system.
/var/log - Stores log files for various system programs. (You may not have permission to look at everything in this directory. Don't let that stop you exploring though. A few error messages never hurt anyone.)
/bin - The location of several commonly used programs (some of which we will learn about in the rest of this tutorial.
/usr/bin - Another location for programs on the system.

ls /etc
bash.bash_logout  fstab            hosts                mtab@          package-versions.txt  profile.d/  tigrc
bash.bashrc       gitattributes    inputrc              nanorc         pkcs11/               protocols   vimrc
DIR_COLORS        git-bash.config  install-options.txt  networks       pki/                  services
docx2txt.config   gitconfig        msystem              nsswitch.conf  profile               ssh/

ls /var/log
ls: cannot access '/var/log': No such file or directory

 ls /bin
'[.exe'*                      gobject-query.exe*              msys-heimbase-1.dll*          rnano.exe*
 addgnupghome*                gpg.exe*                        msys-heimntlm-0.dll*          runcon.exe*
 applygnupgdefaults*          gpg-agent.exe*                  msys-history8.dll*            rview.exe*
 arch.exe*                    gpgconf.exe*                    msys-hogweed-6.dll*           rvim.exe*
 astextplain*                 gpg-connect-agent.exe*          msys-hx509-5.dll*             sasldblistusers2.exe*
 autopoint*                   gpg-error.exe*                  msys-iconv-2.dll*             saslpasswd2.exe*
 awk.exe*                     gpgparsemail.exe*               msys-idn2-0.dll*              scp.exe*
 b2sum.exe*                   gpgscm.exe*                     msys-intl-8.dll*              sdiff.exe*
 backup*                      gpgsm.exe*                      msys-kadm5clnt-7.dll*         sed.exe*
 base32.exe*                  gpgtar.exe*                     msys-kadm5srv-8.dll*          seq.exe*
 base64.exe*                  gpgv.exe*                       msys-kafs-0.dll*              setfacl.exe*
 basename.exe*                gpg-wks-server.exe*             msys-kdc-2.dll*               setmetamode.exe*
 basenc.exe*                  grep.exe*                       msys-krb5-26.dll*             sexp-conv.exe*
 bash.exe*                    groups.exe*                     msys-ksba-8.dll*              sftp.exe*
 bashbug*                     gsettings.exe*                  msys-lz4-1.dll*               sh.exe*
 bunzip2.exe*                 gunzip*                         msys-lzma-5.dll*              sha1sum.exe*
 bzcat.exe*                   gzexe*                          msys-magic-1.dll*             sha224sum.exe*
 bzcmp*                       gzip.exe*                       msys-menuw6.dll*              sha256sum.exe*
 bzdiff*                      head.exe*                       msys-metalink-3.dll*          sha384sum.exe*
 bzegrep*                     hmac256.exe*                    msys-mpfr-6.dll*              sha512sum.exe*
 bzfgrep*                     hostid.exe*                     msys-ncurses++w6.dll*         shred.exe*
 bzgrep*                      hostname.exe*                   msys-ncursesw6.dll*           shuf.exe*
 bzip2.exe*                   iconv.exe*                      msys-nettle-8.dll*            sleep.exe*
 bzip2recover.exe*            id.exe*                         msys-nghttp2-14.dll*          sort.exe*
 bzless*                      infocmp.exe*                    msys-npth-0.dll*              split.exe*
 bzmore*                      infotocap.exe*                  msys-p11-kit-0.dll*           ssh.exe*
 c_rehash*                    install.exe*                    msys-panelw6.dll*             ssh-add.exe*
 captoinfo.exe*               join.exe*                       msys-pcre-1.dll*              ssh-agent.exe*
 cat.exe*                     kbxutil.exe*                    msys-pcre2-8-0.dll*           ssh-copy-id*
 chattr.exe*                  kill.exe*                       msys-perl5_32.dll*            sshd.exe*
 chcon.exe*                   ldd.exe*                        msys-psl-5.dll*               ssh-keygen.exe*
 chgrp.exe*                   ldh.exe*                        msys-readline8.dll*           ssh-keyscan.exe*
 chmod.exe*                   less.exe*                       msys-roken-18.dll*            ssh-pageant.exe*
 chown.exe*                   lessecho.exe*                   msys-sasl2-3.dll*             ssp.exe*
 chroot.exe*                  lesskey.exe*                    msys-serf-1-0.dll*            start*
 cksum.exe*                   link.exe*                       msys-sl-0.dll*                stat.exe*
 clear.exe*                   ln.exe*                         msys-smartcols-1.dll*         strace.exe*
 cmp.exe*                     locale.exe*                     msys-sqlite3-0.dll*           stty.exe*
 column.exe*                  locate.exe*                     msys-ssh2-1.dll*              sum.exe*
 comm.exe*                    logname.exe*                    msys-ssl-1.1.dll*             sync.exe*
 core_perl/                   ls.exe*                         msys-svn_client-1-0.dll*      tabs.exe*
 cp.exe*                      lsattr.exe*                     msys-svn_delta-1-0.dll*       tac.exe*
 csplit.exe*                  mac2unix.exe*                   msys-svn_diff-1-0.dll*        tail.exe*
 cut.exe*                     md5sum.exe*                     msys-svn_fs_fs-1-0.dll*       tar.exe*
 cygcheck.exe*                minidumper.exe*                 msys-svn_fs_util-1-0.dll*     tee.exe*
 cygpath.exe*                 mintheme*                       msys-svn_fs_x-1-0.dll*        test.exe*
 cygwin-console-helper.exe*   mintty.exe*                     msys-svn_fs-1-0.dll*          tic.exe*
 d2u.exe*                     mkdir.exe*                      msys-svn_ra_local-1-0.dll*    tig.exe*
 dash.exe*                    mkfifo.exe*                     msys-svn_ra_serf-1-0.dll*     timeout.exe*
 date.exe*                    mkgroup.exe*                    msys-svn_ra_svn-1-0.dll*      toe.exe*
 dd.exe*                      mknod.exe*                      msys-svn_ra-1-0.dll*          touch.exe*
 df.exe*                      mkpasswd.exe*                   msys-svn_repos-1-0.dll*       tput.exe*
 diff.exe*                    mktemp.exe*                     msys-svn_subr-1-0.dll*        tr.exe*
 diff3.exe*                   mount.exe*                      msys-svn_swig_perl-1-0.dll*   true.exe*
 dir.exe*                     mpicalc.exe*                    msys-svn_swig_py-1-0.dll*     truncate.exe*
 dircolors.exe*               msgattrib.exe*                  msys-svn_swig_ruby-1-0.dll*   trust.exe*
 dirmngr.exe*                 msgcat.exe*                     msys-svn_wc-1-0.dll*          tset.exe*
 dirmngr-client.exe*          msgcmp.exe*                     msys-tasn1-6.dll*             tsort.exe*
 dirname.exe*                 msgcomm.exe*                    msys-ticw6.dll*               tty.exe*
 docx2txt*                    msgconv.exe*                    msys-unistring-2.dll*         tzset.exe*
 docx2txt.pl*                 msgen.exe*                      msys-uuid-1.dll*              u2d.exe*
 dos2unix.exe*                msgexec.exe*                    msys-wind-0.dll*              umount.exe*
 du.exe*                      msgfilter.exe*                  msys-xml2-2.dll*              uname.exe*
 dumpsexp.exe*                msgfmt.exe*                     msys-xslt-1.dll*              uncompress*
 echo.exe*                    msggrep.exe*                    msys-z.dll*                   unexpand.exe*
 egrep*                       msginit.exe*                    mv.exe*                       uniq.exe*
 env.exe*                     msgmerge.exe*                   nano.exe*                     unix2dos.exe*
 envsubst.exe*                msgunfmt.exe*                   nettle-hash.exe*              unix2mac.exe*
 ex.exe*                      msguniq.exe*                    nettle-lfib-stream.exe*       unlink.exe*
 expand.exe*                  msys-2.0.dll*                   nettle-pbkdf2.exe*            unzip.exe*
 expr.exe*                    msys-apr-1-0.dll*               ngettext.exe*                 unzipsfx.exe*
 factor.exe*                  msys-aprutil-1-0.dll*           nice.exe*                     update-ca-trust*
 false.exe*                   msys-asn1-8.dll*                nl.exe*                       updatedb*
 fgrep*                       msys-asprintf-0.dll*            nohup.exe*                    users.exe*
 fido2-assert.exe*            msys-assuan-0.dll*              notepad*                      vdir.exe*
 fido2-cred.exe*              msys-atomic-1.dll*              nproc.exe*                    vendor_perl/
 fido2-token.exe*             msys-blkid-1.dll*               numfmt.exe*                   vi*
 file.exe*                    msys-bz2-1.dll*                 od.exe*                       view.exe*
 find.exe*                    msys-cbor-0.dll*                openssl.exe*                  vim.exe*
 findssl.sh*                  msys-charset-1.dll*             p11-kit.exe*                  vimdiff.exe*
 fmt.exe*                     msys-com_err-1.dll*             passwd.exe*                   vimtutor*
 fold.exe*                    msys-crypt-0.dll*               paste.exe*                    watchgnupg.exe*
 funzip.exe*                  msys-crypto-1.1.dll*            patch.exe*                    wc.exe*
 gapplication.exe*            msys-curl-4.dll*                pathchk.exe*                  which.exe*
 gawk.exe*                    msys-edit-0.dll*                perl.exe*                     who.exe*
 gawk-5.0.0.exe*              msys-expat-1.dll*               perl5.32.0.exe*               whoami.exe*
 gdbus.exe*                   msys-exslt-0.dll*               pinentry.exe*                 winpty.dll*
 gencat.exe*                  msys-fdisk-1.dll*               pinentry-w32.exe*             winpty.exe*
 getconf.exe*                 msys-ffi-7.dll*                 pinky.exe*                    winpty-agent.exe*
 getemojis*                   msys-fido2-1.dll*               pkcs1-conv.exe*               winpty-debugserver.exe*
 getfacl.exe*                 msys-formw6.dll*                pldd.exe*                     wordpad*
 getopt.exe*                  msys-gcc_s-seh-1.dll*           pluginviewer.exe*             xargs.exe*
 gettext.exe*                 msys-gcrypt-20.dll*             pr.exe*                       xgettext.exe*
 gettext.sh*                  msys-gettextlib-0-19-8-1.dll*   printenv.exe*                 xxd.exe*
 gettextize*                  msys-gettextpo-0.dll*           printf.exe*                   yat2m.exe*
 gio-querymodules.exe*        msys-gettextsrc-0-19-8-1.dll*   ps.exe*                       yes.exe*
 git-flow*                    msys-gio-2.0-0.dll*             psl.exe*                      zcat*
 git-flow-bugfix              msys-glib-2.0-0.dll*            psl-make-dafsa*               zcmp*
 gitflow-common               msys-gmodule-2.0-0.dll*         ptx.exe*                      zdiff*
 git-flow-config              msys-gmp-10.dll*                pwd.exe*                      zegrep*
 git-flow-feature             msys-gmpxx-4.dll*               readlink.exe*                 zfgrep*
 git-flow-hotfix              msys-gnutls-30.dll*             realpath.exe*                 zforce*
 git-flow-init                msys-gnutlsxx-28.dll*           rebase.exe*                   zgrep*
 git-flow-log                 msys-gobject-2.0-0.dll*         rebaseall*                    zipgrep*
 git-flow-release             msys-gomp-1.dll*                recode-sr-latin.exe*          zipinfo.exe*
 gitflow-shFlags              msys-gpg-error-0.dll*           regtool.exe*                  zless*
 git-flow-support             msys-gssapi-3.dll*              reset.exe*                    zmore*
 git-flow-version             msys-gthread-2.0-0.dll*         restore*                      znew*
 gkill.exe*                   msys-hcrypto-4.dll*             rm.exe*
 glib-compile-schemas.exe*    msys-hdb-9.dll*                 rmdir.exe*
 
  ls /usr/bin
'[.exe'*                      gobject-query.exe*              msys-heimbase-1.dll*          rnano.exe*
 addgnupghome*                gpg.exe*                        msys-heimntlm-0.dll*          runcon.exe*
 applygnupgdefaults*          gpg-agent.exe*                  msys-history8.dll*            rview.exe*
 arch.exe*                    gpgconf.exe*                    msys-hogweed-6.dll*           rvim.exe*
 astextplain*                 gpg-connect-agent.exe*          msys-hx509-5.dll*             sasldblistusers2.exe*
 autopoint*                   gpg-error.exe*                  msys-iconv-2.dll*             saslpasswd2.exe*
 awk.exe*                     gpgparsemail.exe*               msys-idn2-0.dll*              scp.exe*
 b2sum.exe*                   gpgscm.exe*                     msys-intl-8.dll*              sdiff.exe*
 backup*                      gpgsm.exe*                      msys-kadm5clnt-7.dll*         sed.exe*
 base32.exe*                  gpgtar.exe*                     msys-kadm5srv-8.dll*          seq.exe*
 base64.exe*                  gpgv.exe*                       msys-kafs-0.dll*              setfacl.exe*
 basename.exe*                gpg-wks-server.exe*             msys-kdc-2.dll*               setmetamode.exe*
 basenc.exe*                  grep.exe*                       msys-krb5-26.dll*             sexp-conv.exe*
 bash.exe*                    groups.exe*                     msys-ksba-8.dll*              sftp.exe*
 bashbug*                     gsettings.exe*                  msys-lz4-1.dll*               sh.exe*
 bunzip2.exe*                 gunzip*                         msys-lzma-5.dll*              sha1sum.exe*
 bzcat.exe*                   gzexe*                          msys-magic-1.dll*             sha224sum.exe*
 bzcmp*                       gzip.exe*                       msys-menuw6.dll*              sha256sum.exe*
 bzdiff*                      head.exe*                       msys-metalink-3.dll*          sha384sum.exe*
 bzegrep*                     hmac256.exe*                    msys-mpfr-6.dll*              sha512sum.exe*
 bzfgrep*                     hostid.exe*                     msys-ncurses++w6.dll*         shred.exe*
 bzgrep*                      hostname.exe*                   msys-ncursesw6.dll*           shuf.exe*
 bzip2.exe*                   iconv.exe*                      msys-nettle-8.dll*            sleep.exe*
 bzip2recover.exe*            id.exe*                         msys-nghttp2-14.dll*          sort.exe*
 bzless*                      infocmp.exe*                    msys-npth-0.dll*              split.exe*
 bzmore*                      infotocap.exe*                  msys-p11-kit-0.dll*           ssh.exe*
 c_rehash*                    install.exe*                    msys-panelw6.dll*             ssh-add.exe*
 captoinfo.exe*               join.exe*                       msys-pcre-1.dll*              ssh-agent.exe*
 cat.exe*                     kbxutil.exe*                    msys-pcre2-8-0.dll*           ssh-copy-id*
 chattr.exe*                  kill.exe*                       msys-perl5_32.dll*            sshd.exe*
 chcon.exe*                   ldd.exe*                        msys-psl-5.dll*               ssh-keygen.exe*
 chgrp.exe*                   ldh.exe*                        msys-readline8.dll*           ssh-keyscan.exe*
 chmod.exe*                   less.exe*                       msys-roken-18.dll*            ssh-pageant.exe*
 chown.exe*                   lessecho.exe*                   msys-sasl2-3.dll*             ssp.exe*
 chroot.exe*                  lesskey.exe*                    msys-serf-1-0.dll*            start*
 cksum.exe*                   link.exe*                       msys-sl-0.dll*                stat.exe*
 clear.exe*                   ln.exe*                         msys-smartcols-1.dll*         strace.exe*
 cmp.exe*                     locale.exe*                     msys-sqlite3-0.dll*           stty.exe*
 column.exe*                  locate.exe*                     msys-ssh2-1.dll*              sum.exe*
 comm.exe*                    logname.exe*                    msys-ssl-1.1.dll*             sync.exe*
 core_perl/                   ls.exe*                         msys-svn_client-1-0.dll*      tabs.exe*
 cp.exe*                      lsattr.exe*                     msys-svn_delta-1-0.dll*       tac.exe*
 csplit.exe*                  mac2unix.exe*                   msys-svn_diff-1-0.dll*        tail.exe*
 cut.exe*                     md5sum.exe*                     msys-svn_fs_fs-1-0.dll*       tar.exe*
 cygcheck.exe*                minidumper.exe*                 msys-svn_fs_util-1-0.dll*     tee.exe*
 cygpath.exe*                 mintheme*                       msys-svn_fs_x-1-0.dll*        test.exe*
 cygwin-console-helper.exe*   mintty.exe*                     msys-svn_fs-1-0.dll*          tic.exe*
 d2u.exe*                     mkdir.exe*                      msys-svn_ra_local-1-0.dll*    tig.exe*
 dash.exe*                    mkfifo.exe*                     msys-svn_ra_serf-1-0.dll*     timeout.exe*
 date.exe*                    mkgroup.exe*                    msys-svn_ra_svn-1-0.dll*      toe.exe*
 dd.exe*                      mknod.exe*                      msys-svn_ra-1-0.dll*          touch.exe*
 df.exe*                      mkpasswd.exe*                   msys-svn_repos-1-0.dll*       tput.exe*
 diff.exe*                    mktemp.exe*                     msys-svn_subr-1-0.dll*        tr.exe*
 diff3.exe*                   mount.exe*                      msys-svn_swig_perl-1-0.dll*   true.exe*
 dir.exe*                     mpicalc.exe*                    msys-svn_swig_py-1-0.dll*     truncate.exe*
 dircolors.exe*               msgattrib.exe*                  msys-svn_swig_ruby-1-0.dll*   trust.exe*
 dirmngr.exe*                 msgcat.exe*                     msys-svn_wc-1-0.dll*          tset.exe*
 dirmngr-client.exe*          msgcmp.exe*                     msys-tasn1-6.dll*             tsort.exe*
 dirname.exe*                 msgcomm.exe*                    msys-ticw6.dll*               tty.exe*
 docx2txt*                    msgconv.exe*                    msys-unistring-2.dll*         tzset.exe*
 docx2txt.pl*                 msgen.exe*                      msys-uuid-1.dll*              u2d.exe*
 dos2unix.exe*                msgexec.exe*                    msys-wind-0.dll*              umount.exe*
 du.exe*                      msgfilter.exe*                  msys-xml2-2.dll*              uname.exe*
 dumpsexp.exe*                msgfmt.exe*                     msys-xslt-1.dll*              uncompress*
 echo.exe*                    msggrep.exe*                    msys-z.dll*                   unexpand.exe*
 egrep*                       msginit.exe*                    mv.exe*                       uniq.exe*
 env.exe*                     msgmerge.exe*                   nano.exe*                     unix2dos.exe*
 envsubst.exe*                msgunfmt.exe*                   nettle-hash.exe*              unix2mac.exe*
 ex.exe*                      msguniq.exe*                    nettle-lfib-stream.exe*       unlink.exe*
 expand.exe*                  msys-2.0.dll*                   nettle-pbkdf2.exe*            unzip.exe*
 expr.exe*                    msys-apr-1-0.dll*               ngettext.exe*                 unzipsfx.exe*
 factor.exe*                  msys-aprutil-1-0.dll*           nice.exe*                     update-ca-trust*
 false.exe*                   msys-asn1-8.dll*                nl.exe*                       updatedb*
 fgrep*                       msys-asprintf-0.dll*            nohup.exe*                    users.exe*
 fido2-assert.exe*            msys-assuan-0.dll*              notepad*                      vdir.exe*
 fido2-cred.exe*              msys-atomic-1.dll*              nproc.exe*                    vendor_perl/
 fido2-token.exe*             msys-blkid-1.dll*               numfmt.exe*                   vi*
 file.exe*                    msys-bz2-1.dll*                 od.exe*                       view.exe*
 find.exe*                    msys-cbor-0.dll*                openssl.exe*                  vim.exe*
 findssl.sh*                  msys-charset-1.dll*             p11-kit.exe*                  vimdiff.exe*
 fmt.exe*                     msys-com_err-1.dll*             passwd.exe*                   vimtutor*
 fold.exe*                    msys-crypt-0.dll*               paste.exe*                    watchgnupg.exe*
 funzip.exe*                  msys-crypto-1.1.dll*            patch.exe*                    wc.exe*
 gapplication.exe*            msys-curl-4.dll*                pathchk.exe*                  which.exe*
 gawk.exe*                    msys-edit-0.dll*                perl.exe*                     who.exe*
 gawk-5.0.0.exe*              msys-expat-1.dll*               perl5.32.0.exe*               whoami.exe*
 gdbus.exe*                   msys-exslt-0.dll*               pinentry.exe*                 winpty.dll*
 gencat.exe*                  msys-fdisk-1.dll*               pinentry-w32.exe*             winpty.exe*
 getconf.exe*                 msys-ffi-7.dll*                 pinky.exe*                    winpty-agent.exe*
 getemojis*                   msys-fido2-1.dll*               pkcs1-conv.exe*               winpty-debugserver.exe*
 getfacl.exe*                 msys-formw6.dll*                pldd.exe*                     wordpad*
 getopt.exe*                  msys-gcc_s-seh-1.dll*           pluginviewer.exe*             xargs.exe*
 gettext.exe*                 msys-gcrypt-20.dll*             pr.exe*                       xgettext.exe*
 gettext.sh*                  msys-gettextlib-0-19-8-1.dll*   printenv.exe*                 xxd.exe*
 gettextize*                  msys-gettextpo-0.dll*           printf.exe*                   yat2m.exe*
 gio-querymodules.exe*        msys-gettextsrc-0-19-8-1.dll*   ps.exe*                       yes.exe*
 git-flow*                    msys-gio-2.0-0.dll*             psl.exe*                      zcat*
 git-flow-bugfix              msys-glib-2.0-0.dll*            psl-make-dafsa*               zcmp*
 gitflow-common               msys-gmodule-2.0-0.dll*         ptx.exe*                      zdiff*
 git-flow-config              msys-gmp-10.dll*                pwd.exe*                      zegrep*
 git-flow-feature             msys-gmpxx-4.dll*               readlink.exe*                 zfgrep*
 git-flow-hotfix              msys-gnutls-30.dll*             realpath.exe*                 zforce*
 git-flow-init                msys-gnutlsxx-28.dll*           rebase.exe*                   zgrep*
 git-flow-log                 msys-gobject-2.0-0.dll*         rebaseall*                    zipgrep*
 git-flow-release             msys-gomp-1.dll*                recode-sr-latin.exe*          zipinfo.exe*
 gitflow-shFlags              msys-gpg-error-0.dll*           regtool.exe*                  zless*
 git-flow-support             msys-gssapi-3.dll*              reset.exe*                    zmore*
 git-flow-version             msys-gthread-2.0-0.dll*         restore*                      znew*
 gkill.exe*                   msys-hcrypto-4.dll*             rm.exe*
 glib-compile-schemas.exe*    msys-hdb-9.dll*                 rmdir.exe*
 
 
