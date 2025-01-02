*****************extracting job id from success message
String successmsg = successlabel.gettext();
String[] parts = successmsg.split("");
String orderid = parts[8];
System.out.println(orderid)
