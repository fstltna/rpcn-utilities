# RPCN Management Console (1.0.0)
Allows you to manage your RPCN server with a text based UI - 

---

Edit "rmc" and change the settings at the top if your RPCN server is not in /root/rpcn/target/release/.

You also need to have my RPCN Startup Script installed.

I suggest you then add this to your /root/.bashrc file:

-	export PATH=/root/bin:/root/rpcn-utilities:$PATH

You will need to install the required perl modules (as root):

- /root/rpcn-utilities/installdeps


After that you should log out and back in and now "rmc" should work.
