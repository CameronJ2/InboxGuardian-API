# What this is used for:
Until I can host this on a public server, we will have to run the BERT API locally. This essentially creates a local server that only your LAN can access. A nice part of the API implementation is that it runs MUCH faster than the previous implementation!

# How to use:
Run a 'pip install flask' to use the flask package, which is a simple package for webapps. Then, simply run the server.py in an editor or just straight from your file explorer (it'll open in command prompt). If your output looks something like this:
PS C:\Projects\SeniorProjectAPI> python -u "c:\Projects\SeniorProjectAPI\server.py"
 * Serving Flask app 'server'
 * Debug mode: off
WARNING: This is a development server. Do not use it in a production deployment. Use a production WSGI server instead.
 * Running on all addresses (0.0.0.0)
 * Running on http://127.0.0.1:5000
 * Running on http://10.0.0.238:5000
Press CTRL+C to quit

Then you're good to go! You can use APItest.py to test to see if your server is running properly, but make sure you run it from a different folder / working directory.



# Alternative Testing:
You can also download and use [Postman](https://www.postman.com) for testing. Set it up something like this:
![image](https://github.com/CameronJ2/InboxGuardian-API/assets/114731000/9d4f4463-20b4-4724-84a8-2dee77a01546)
