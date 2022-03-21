# MountainMath
quiz game by claudiu.

This application was writen in Java for Android devices.

The quests are provided to the application by http requests using GET and the responses are pulled into the DOM page as Json obj.
For using the application you need to call a dinamic web page like PHP/ASPX/JSP page that provides a JSON Objects which contains
the data you need to use into the Android app.
For now the endpoint is http://hostingphpscuola.altervista.org/HistoryReader/domanda.php? with a param called pid that is an integer from 1 to n.

The best practice should be use the REST architecture to obtain information in Json or XML objects.

I hope to help somebody to perform some cool features using a very simple architecture in android.
