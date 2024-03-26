try {
  String url = "(this will be url, find yours by running one html script)";
  java.awt.Desktop.getDesktop().browse(java.net.URI.create(url));
}
catch (java.io.IOException e) {
    System.out.println(e.getMessage());
}
