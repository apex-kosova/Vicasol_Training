## Some useful links
### Improving some components
- John Snyders: Learn all you can do using the Interactive Grid [Cookbook](https://hardlikesoftware.com/weblog/2019/11/04/apex-ig-cookbook-update-for-19-2/)

### Articles about TeamWork organization and deployments
- Explorer UK: [Version control for team work](https://explorer.co.uk/apex-version-control-team-working/) This article also includes a [youtube video](https://youtu.be/vVLi1HFzuiI) 
- Oracle Documentation: [Locking pages](https://docs.oracle.com/html/E39147_04/bldapp005.htm)
- Insum: [Deployments notes](https://insum.ca/oracle-apex-deployments-youre-doing-it-wrong)

### Error Handling documentation
- Joel Kallman: [Details about this incident are available via debug id....](https://joelkallman.blogspot.com/2017/01/details-about-this-incident-are.html)
- Dimitri Gielis: [Automatically capture all errors](http://dgielis.blogspot.com/2018/06/automatically-capture-all-errors-and.html)
- Lucas Rayner: [Exception Handling + APEX_ERROR](https://www.lrayner.com/post/exception-handling-apex_error-oracle-apex-19-1)
- Oracle documentation: [Error Handling](https://docs.oracle.com/database/apex-5.1/AEAPI/Example-of-an-Error-Handling-Function.htm#AEAPI2216)

### Some more notes about App translation
- General App translation: https://www.triology.de/en/blog-entries/database-applications-oracle-apex
- Translating Data (4 point): https://www.oreilly.com/library/view/oracle-apex-cookbook/9781782179672/ch06.html
- Jorge Rimblas' plugin: https://github.com/rimblas/jtlitem / https://apex.world/ords/f?p=100:710:774778306472::::P710_PLG_ID:JMR.MLS.JTLITEM
- Oracle Documentation: [Translation of an app](https://docs.oracle.com/database/121/HTMDB/global_process.htm#HTMDB14003)

### REST Services
- WebServices, by Explorer: (https://explorer.co.uk/web-services-part-1/)
- Oracle Documentation: [HTTP Errors](https://docs.oracle.com/en/cloud/iaas/messaging-cloud/csmes/rest-api-http-status-codes-and-error-messages-reference.html#GUID-F3506024-AF35-4020-98B7-AAEC6C2AC73F)

### Create APEX session to prepare URL from Forms to APEX
The best approach I found is creating a session using a PL/SQL process before creating the navigation link, and then use that session at PREPARE_URL function as a parameter. 

[Deep Linking Doc](https://docs.oracle.com/en/database/oracle/application-express/19.2/htmdb/managing-application-attributes.html#GUID-33A67D5E-1128-4D23-9C5C-15FC9BE1B783)

That way, navigation should work straight forward.

Some usefull links:
- [Oracle's Documentation](https://docs.oracle.com/database/apex-18.1/AEAPI/APEX_SESSION.htm#AEAPI-GUID-348C879F-3B45-4F4E-8641-518C711CE76F)
- Example 1 at [GitHub](https://gist.github.com/hmarques/c8d33afffce9f467f63bcabf0909e520)
- Example 2 at [TalkAPEX blog](https://www.talkapex.com/2012/08/how-to-create-apex-session-in-plsql/)

### Create some more APEX examples
- Rapidly build a time card app using APEX: [YouTube video](https://youtu.be/gvRzsfG2OWc)
- Movies app: [YouTube video](https://youtu.be/VlYa5xkF_kE)

### Some more usefull links:
- PinkDB Architecture and APEX: [Insum YouTube video](https://youtu.be/v2keRdIODnk)
