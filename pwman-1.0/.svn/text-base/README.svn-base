 $$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$
[                                                                              ]

                            mio, vimscripts.org
                             http://rlogin.dk
                                bring you
 
                    XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                      No fuzz password manager in bash
                    XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX
                             by Michael Olsen
                                gnu@gmx.net
                                 2008-02
[                                                                              ]
 $$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$$

                              What is pwman?
                               ~~~~~~~~~~~~
Pwman is a password manager written in bash with a curses frontend,
minimalistic design, vim and gpg encryption of your files in an easy way.
Takes only a second to create a new encrypted file or edit an old one.

                                 Features
                               ~~~~~~~~~~~~
Tired of password managers written in python, haskell or fortran?
with this small bash script without any critical dependencies (should work 
out of the box with even a base debian install)
you can manage your passwords easily and secure with as many encrypting
bits as you like in your favorite editor (vim/gpg frontend).

This script is a frontend to the vim gpg decryption macro originally
based on the one from vimscripts.org but it is a bit modified).


With the following script you will be able to open .gpg files and 
encrypt them as soon as you save them, automagically.

                                 Technical
                               ~~~~~~~~~~~~
As many encrypting bits as GPG supports (4096 normally)
Doesn't save /tmp files that are insecure
Takes security very serious, program should be safe to use.
Everytime you create a new encrypted file it is saved in ~/.gpg with 700 perm

Program is a dialog(1)/vim frontend to GPG.

                                 Install
                               ~~~~~~~~~~~~
See the INSTALL file in this directory, there are no dependencies except
a base gnu system(dialog being part thereof), vim and gpg.
Yes - almost too good to be true :)

                                  Usage
                               ~~~~~~~~~~~~
Simple type 'pwman' to start the GUI frontend, to create/edit/delete 
encrypted files.

or cd ~/.gpg , then pwman encryptedfile.gpg

                                 Version
                               ~~~~~~~~~~~~
For version information please run pwman --version.
Latest stable releases can be found on gnu.org ftp or author's homepage
http://rlogin.dk/pwman

                                  NOTICE
                               ~~~~~~~~~~~~
This software is free software, you must ship the original credits and
this file with this software, it is licensed under GPLv3.
If you edit it, you must redistrubute the source with the new version!

Send to people you know, we all need a simple and safe password manager
if you improve it, with ncurses i.e. send back a patch
although this one is more portable, doesn't require libncurses, it uses
dialog(1) which is with most linux dists today (is in GNU base).

The GPLv3 license that you agree to by using this software can be found
in 'COPYING' with this software or on www.gnu.org
