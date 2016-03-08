This is a simple API to access Amazon's SQS, EC2, CloudWatch, AutoScaling, ELB, SimpleDB, SNS, FPS and DevPay LS web services. It uses the QUERY APIs. This code is thread-safe and works very reliably to the best of my knowledge. I've been using it on a system where sending messages in SQS is critical and we manage pools of servers on EC2.

Typica has been tested with the Eucalyptus Community Cloud (http://ecc.eucalyptus.com).

NOTE: The 1.7 release brings support for HttpClient 4, which means a change to the dependencies. Please download the newer httpclient/httpcore jars.

**How are you using typica? I'd like to hear about your application! Send me a URL and/or description. TypicaInTheWild**

There is a new tool available for downloads. QueryTool is helpful for debugging select statements in SimpleDB. For more information, look here; http://coderslike.us/2009/04/15/query-tool-for-amazon-simpledb/

Dependencies:
  * commons-logging (http://commons.apache.org/downloads/download_logging.cgi)
  * JAXB (https://jaxb.dev.java.net/servlets/ProjectDocumentList?folderID=6746&expandFolder=6746&folderID=3952)
  * httpclient 4 (http://hc.apache.org/downloads.cgi)
  * commons-codec (http://commons.apache.org/downloads/download_codec.cgi)

The combination of EC2, S3 and SQS is very compelling for building scalable applications. Instead of adding S3 support into typica, I recommend using the excellent library called Jets3t. http://jets3t.s3.amazonaws.com/index.html

This project is referenced at the AWS Developer's Connection: http://developer.amazonwebservices.com/connect/entry.jspa?externalID=770

The name (TIP-ik-uh) was chosen because this is a coffee grown in Brazil, through which the Amazon flows. (has the Java and Amazon references)

Get your "typica" mug here! http://www.cafepress.com/coderslikeus.376764639

&lt;wiki:gadget url="http://www.ohloh.net/p/16208/widgets/project\_thin\_badge.xml" height="36"  border="0" /&gt;