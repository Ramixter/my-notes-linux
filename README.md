# Linux permissions

Let's practise a little. We'll talk about permissions.

<mark style="background-color:purple;">Remember</mark> that we can use the "<mark style="color:yellow;">`sudo su`</mark>" command to become the "`root`" user.

```bash
sudo su
```

If we now used the "`whoami`" command, we would see that we have become the "`root`" user (or superuser inside the machine).

{% hint style="info" %}
Command "<mark style="color:yellow;">`whoami`</mark>" shows you who is currently logged in.
{% endhint %}

{% hint style="info" %}
If we were to use the "<mark style="color:yellow;">`cd`</mark>`"` command, it would take us to the home folder of the user who is currently logged in.
{% endhint %}

Let's get to work!

Go to the folder of any user (e.g. the user "ramiro"). <mark style="background-color:purple;">Remember:</mark> We use the "<mark style="color:yellow;">`ls`</mark>" command to list the contents of a directory. And now we will be able to see a series of permissions on the files and directories of the folder in which we are currently located.

