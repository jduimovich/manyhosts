# manyhosts

Some sample code to demo hosts issues on crc.

oc apply -f routes 

and you should see all the routes in your hosts file. All except one is missing in my crc

I also built the admin-helper from  https://github.com/praveenkumar/admin-helper.git and it seems to work fine.
This means crc may be mismatched or my configuration is strange.

The scripts addhosts.cmd and removehosts.cmd --- you need to modify the files to point to your admin-helper and run in admin-mode
but it adds and deletes as expected. 
