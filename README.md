Orbeon Forms - Open source web forms done the right way
=======================================================

Last updated for Orbeon Forms 4.3 July 2013

[![Build Status](https://secure.travis-ci.org/orbeon/orbeon-forms.png)](http://travis-ci.org/orbeon/orbeon-forms)

What is Orbeon Forms?
---------------------

Orbeon Forms is an open source, standard-based web forms solution, which
includes:

- Form Builder, the WYSIWYG browser-based authoring tool
- Form Runner, the runtime environment which facilitates the deployment and
  integration of large and complex forms
- A core forms processing engine which implements specifications such as XForms 1.1
  and XBL 2 with no need for client-side software besides a standard web browser.

For more information about Orbeon Forms, please visit:

- <http://www.orbeon.com/>
- <http://wiki.orbeon.com/forms/>

Also check the Orbeon Forms [Frequently Asked Questions (FAQ)](http://wiki.orbeon.com/forms/orbeon-forms-faq).


What's new in the latest releases
---------------------------------

- [complete list of changes](http://wiki.orbeon.com/forms/doc/developer-guide/release-notes/40) for the latest release
- [Orbeon Forms 4.2 announcement](http://blog.orbeon.com/2013/05/orbeon-forms-42.html)
- [Orbeon Forms 4.1 announcement](http://blog.orbeon.com/2013/04/orbeon-forms-41.html)
- [Orbeon Forms 4.0.1 announcement](http://blog.orbeon.com/2013/03/orbeon-forms-401.html)
- [Orbeon Forms 4.0 announcement](http://blog.orbeon.com/2013/03/announcing-orbeon-forms-40.html)


Downloading and installing
--------------------------

Orbeon Forms comes in two editions:

- Community Edition (CE)
- Professional edition (PE)

For more information and downloadable binaries, see the [download](http://www.orbeon.com/download) page.

The system requirements and installation procedure are detailed on
[Installing Orbeon Forms](http://wiki.orbeon.com/forms/doc/developer-guide/admin/installing).


Community and support
---------------------

See the [community](http://www.orbeon.com/community) page. In a nutshell:

- Ask short questions directed to Orbeon on [Twitter](https://twitter.com/intent/tweet?in_reply_to=orbeon&in_reply_to_status_id=261900968369729536&source=webclient&text=%40orbeon+).
- Asl technical questions on [StackOverflow](http://stackoverflow.com/questions/ask?tags=orbeon) (don't forget the "orbeon" tag).
- Use the [discussion forum](http://discuss.orbeon.com/) for discussions and feedback.
- For commercial support and licensing, see:
    - <http://www.orbeon.com/services>
    - <info@orbeon.com>


Documentation
-------------

All documentation is available on the [Orbeon Forms wiki](http://wiki.orbeon.com/forms/).


What's happening?
-----------------

- Orbeon Blog: <http://blog.orbeon.com/>
- Orbeon on Twitter: <http://twitter.com/orbeon>
- Latest commits on github: <https://github.com/orbeon/orbeon-forms/commits/>
- Mailing-list archive: <http://orbeon-forms-ops-users.24843.n4.nabble.com/>


Compiling Orbeon Forms
----------------------

You usually don't have to compile Orbeon Forms yourself. But if you want to, see
[Java development and IDE settings](http://wiki.orbeon.com/forms/doc/contributor-guide/development-environment/java-development).
The source code is available on [github](https://github.com/orbeon/orbeon-forms/).

Orbeon Forms is written mainly using the following languages and technologies:

- Java
- Scala
- JavaScript
- CoffeeScript
- XForms, XSLT, and other XML technologies


Known bugs and requests for enhancements (RFEs)
-----------------------------------------------

For a list of known issues and RFEs, check the [issue tracking system](https://github.com/orbeon/orbeon-forms/issues).


License
-------

The source code is distributed under the terms of the GNU Lesser General
Public License (LGPL). The full text of the license is available at
<http://www.gnu.org/copyleft/lesser.html>. LGPL is a business-friendly
license that allows you to use Orbeon Forms for open source and
commercial applications.

Some examples are distributed under the terms of the Apache License,
Version 2.0. The full text of the license is available at:
<http://www.apache.org/licenses/LICENSE-2.0>.

Please refer to file headers to identify which license governs the
distribution of a particular file.

This software is OSI Certified Open Source Software. OSI Certified is
a certification mark of the Open Source Initiative.

See the next section for more details about the licenses of included
third-party software.


Third-party software
--------------------

This product includes software developed by the Apache Software Foundation
(http://www.apache.org/):

- Ant (<http://ant.apache.org/>)
- Avalon (<http://avalon.apache.org/closed.html>)
- Axis (<http://axis.apache.org/>)
- Batik (<http://xmlgraphics.apache.org/batik/>)
- Commons (<http://commons.apache.org/>)
- FOP (<http://xmlgraphics.apache.org/fop/>)
- HttpComponents (<http://hc.apache.org/>)
- log4j (<http://logging.apache.org/log4j/>)
- Mime4j (<http://james.apache.org/mime4j/>)
- POI (<http://poi.apache.org/>)
- Xerces (<http://xerces.apache.org/xerces-j/>)

In addition, this product includes the following software:

- antlr (<http://www.antlr.org/>)
- Barcode4j (<http://barcode4j.sourceforge.net/>)
- Castor (<http://www.castor.org/>)
- CoffeeScript (<http://jashkenas.github.com/coffee-script/>)
- dom4j (<http://dom4j.org/>)
- Ehcache (<http://ehcache.org/>)
- eXist (<http://exist.sourceforge.net/>)
- Flying Saucer (<http://code.google.com/p/flying-saucer/>)
- hsqldb (<http://hsqldb.sourceforge.net/>)
- iText (<http://itextpdf.com/>)
- Jaxen (<http://jaxen.org/>)
- JCIFS (<http://jcifs.samba.org/>)
- JCommon (<http://www.jfree.org/jcommon/>)
- JFreeChart (<http://www.jfree.org/jfreechart/>)
- JTidy (<http://jtidy.sourceforge.net/>)
- JUnit (<http://www.junit.org/>)
- PDFBox (<http://pdfbox.apache.org/>)
- Rhino (<http://www.mozilla.org/rhino/>)
- Saxon (<http://saxon.sourceforge.net/>)
- SAXPath (<http://sourceforge.net/projects/saxpath/>)
- Scala (<http://www.scala-lang.org/>)
- ScalaTest (<http://www.scalatest.org/>)
- TagSoup (<http://home.ccil.org/~cowan/XML/tagsoup/>)
- Sun Multi-Schema XML Validator (<https://msv.dev.java.net/>)
- YUI Compressor (<http://developer.yahoo.com/yui/compressor/>)
- YUI Library (<http://developer.yahoo.com/yui/>)

This product makes use of schemas for XSLT 2.0 and XForms 1.1 provided
under W3C Software License. The schemas are available at the following
locations:

    jar:orbeon.jar!/org/orbeon/oxf/xml/schemas/xslt-2_0.xsd
    jar:orbeon-resources-private.jar!/ops/xforms/schema/*.rn[c|g]

This product makes use of the Silk Icons, released under a Creative Commons
Attribution 2.5 License: http://www.famfamfam.com/lab/icons/silk/

This product makes use of the PixelMixer icons at http://pixel-mixer.com/

Please consult the third-party-licenses directory for more information
about individual licenses.

Credits
-------

We would like to thank [YourKit, LLC](http://www.yourkit.com/) for kindly supporting open source projects like Orbeon
Forms with the full-featured [YourKit Java Profiler](http://www.yourkit.com/java/profiler/index.jsp).

---

Copyright 1999-2013 (C) Orbeon, Inc. All rights reserved.
