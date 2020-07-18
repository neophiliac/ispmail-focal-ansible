# ISPmail Focal (20.04 LTS) Ansible Playbook

This repository contains an Ansible playbook and roles to help set up a mail
servers. I like Debian just fine, but all of my other servers are Ubuntu so
this is too, to avoid stupid admin errors (or maybe stupid-admin errors).

Please see the original instructions at
https://workaround.org/ispmail/buster/ansible

The Vagrantfile is for testing changes to the playbooks. Get Vagrant from
https://www.vagrantup.com/downloads.html (you'll need a virtualization system;
VirtualBox is the default) and once it's installed, run `vagrant up` from this
directory. 

To run Ansible, you'll need to have ansible installed (obviously). If you have
Python on your workstation you can use `pip install ansible` or check your
package manager.

# License

Christoph Haas at workaround.org said in the original README "Everything in
this repository can be freely used under the terms of the MIT license."

To do this right, here is the text of the MIT license that is required to make
use of this software under that license. I'm guessing on the year and ownership.

MIT License

Copyright (c) 2020 Christoph Haas

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
