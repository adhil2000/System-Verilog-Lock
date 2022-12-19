# System-Verilog-Lock
![Lab9](https://user-images.githubusercontent.com/55320801/208475550-2efc7c1e-9e0b-4b6a-9073-7ab2dfb4056e.gif)

For this lab, you will implement a digital combination lock that lets you enter a password to set the lock, and allows you to unlock it by re-entering the password. If you enter an incorrect digit at any point while the lock is secured, the lock will immediately set off an alarm (it's not as dramatic as we would like, but it works for what we have).

The lock is quite simplistic in capability - you first enter a passphrase, using the hex digits 0-F and set it by pressing W. Now in a SECURE state, the lock can be OPENed if you re-enter the same passphrase and press W. You can also relock the lock by pressing Y. Entering the wrong passphrase will cause the lock to sound an alarm and CALL 911.
