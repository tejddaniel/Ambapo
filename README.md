Ambapo
======
How do I execute Ambapo?
Go to "Releases" and click on the most recent release's .jar file link and get to converting!

What is Ambapo? Once I open Ambapo, how do I use it?
Ambapo, named after the Swahili word for "where", allows for the conversion of latitude and longitude, using any geodetic datum, to Universal Transverse Mercator and vice versa. One conversion can be done or a bulk conversion of a CSV file. If converting from UTM to lat/long, the data should be put in the CSV file as follows:

  easting, northing, hemisphere, zone number, zone letter, datum to convert to

None of the numbers should contain commas, as that is how the values are separated. The hemisphere should be denoted as N or S. You do not need (but can still have) both a hemisphere AND a zone letter, but you do need one or the other. If either of this information is missing, put an asterisk (*) in its place. 

If you are converting from Lat Long to UTM, the data should be put in the CSV file as follows:
  latitude, longitude, coordinate's datum

You can have headers or comment out lines that you don't want read by the converter, but please denote these lines with a percent symbol % as the first character of each line with no spaces in front of it.

Thank you, enjoy, and contribute.
