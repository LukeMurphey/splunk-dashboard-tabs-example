I support this app in my free-time and at my own expense. Please consider offering a donation in order to promote continued development. [You can donate on Paypal.](https://www.paypal.com/donate?business=MQSKTS3W7LUTY&item_name=Support+continued+development+of+Splunk+apps&currency_code=USD)

# Tabs on Splunk Dashboards
An example of the use of tabs on a Splunk dashboard.

# Details
This app provides a mechanism for making tabbed panels in Splunk where the searches within the panels are not exeuted until the tab is selected.

See the following blog post for details: http://blogs.splunk.com/2015/03/30/making-a-dashboard-with-tabs-and-searches-that-run-when-clicked/

# Why use tabs (versus other options)

1. This allows users to avoid leaving the dashboard and losing their context (moving between dashboards can be disruptive)
2. This allows users to see the results of other panels without re-running the searches (moving back to prior dashboard would require to rerun the searches)
3. This allows users to not run searches until they want to see the results (if all of the panels are on a single dashboard then all of the searches run when you load the dashboard)
4. This prevents users from excessive scrolling (which would happen if you have them all on a single dashboard)
