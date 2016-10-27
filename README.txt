Sample run from Thu Oct 27 2016 for sword-dev.library.columbia.edu
fcd1@fcd1-parallels-vm-ubuntu:~/Development/python/requests/sword_requests$ python3
Python 3.5.2 (default, Sep 10 2016, 08:21:44)
[GCC 5.4.0 20160609] on linux
Type "help", "copyright", "credits" or "license" for more information.
>>> import sword
>>> sword.set_host('sword-dev.library.columbia.edu')
>>> sword.set_credentials('firsttestdepositor','firstdepositorpasswd')
>>> sword.post_deposit_https('second-test-collection','bmc_07040e0d7efee69e385b8f8f6a15e2ed.zip')
Port not set
<Response [200]>
>>>
