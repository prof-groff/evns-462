## About Datasets

Name: antarctic_ozone.csv</br>
Source: NASA, https://ozonewatch.gsfc.nasa.gov/statistics/ytd_data.txt</br>
Description: Data for the size of the ozone hole and the yearly minimum amount of ozone over Antarctica from 1979 through 2019.</br>

Name: titanic_train.csv titanic_test.csv</br>
Source: Pulled from Kaggle.com on 12/03/21018

Name: winmag-data-130k.tar.gz</br>
Title 130k Wine Reviews from WineEnthusiast</br>
Source: Pulled from Kaggle.com on 12/21/2017, Attributed to zackthoutt, Released Under CC BY-NC-SA 4.0</br>
Descripiton: 130k wine reviews with variety, location, winery, price, and description</br>

The data consists of 10 fields:</br>
Points: the number of points WineEnthusiast rated the wine on a scale of 1-100 (though they say they only post reviews for wines that score >=80)</br>
Title: the title of the wine review, which often contains the vintage if you're interested in extracting that feature</br>
Variety: the type of grapes used to make the wine (ie Pinot Noir)</br>
Description: a few sentences from a sommelier describing the wine's taste, smell, look, feel, etc.</br>
Country: the country that the wine is from</br>
Province: the province or state that the wine is from</br>
Region 1: the wine growing area in a province or state (ie Napa)</br>
Region 2: sometimes there are more specific regions specified within a wine growing area (ie Rutherford inside the Napa Valley), but this value can sometimes be blank</br>
Winery: the winery that made the wine</br>
Designation: the vineyard within the winery where the grapes that made the wine are from</br>
Price: the cost for a bottle of the wine</br>
Taster Name: name of the person who tasted and reviewed the wine</br>
Taster Twitter Handle: Twitter handle for the person who tasted and reviewed the wine</br>
Tests: you name it</br>

Name: cereal.csv</br>
Title: Data for 70+ Cereals</br>
Source: dowloaded 12/18/2017 from the [Kaggle](kaggle.com) public dataset repository. Credited to [Chris Crawford](https://www.kaggle.com/crawford)</br>
Description: Nominal/categorical and ratio/interval data for 70+ different cereals.</br>
Tests: descriptive statistics, t-tests, chi-square test</br>

Name: appletrees.csv</br>
Title: Apple Tree Trunk Girth (mm)</br>
Source: S.C. Pearce, University of Kent at Canterbury</br>
Description: The following data represent trunk girth (mm) of a random sample of 60 four-year-old apple trees at East Malling Research Station (England)</br>
Tests: suitable for descriptive statistic calculations</br>

Name: shoshoni.csv</br>
Title: Width-to-Length Ratio of Shoshoni Handicraft</br>
Source: Dubois, Cora (ed.) (1960). Lowie's Selected Papers in Anthropology. University of California Press, Berkeley.</br>
Description: The data are width-to-length ratios of beaded rectangles used by the Shoshoni Indians of America to decorate their leather goods. One might ask whether the golden rectangle (for which the width-to-length ratio is 0.618) can be considered an aesthetic standard for the Shoshonis just as it was for the Greeks and the Egyptians.</br>
Tests: One-sample t-test against a true mean of 0.618</br>

Name: beerbottle.csv</br>
Title: Measurement of Beer Head Retention</br>
Source: R.G. Ault, E.J. Hudson, D.J. Linehan, and J.D. Woodward (1967).</br>
"A Practical Approach to the Assessment of Head Retention of Bottled Beers,"
Journal of the Institute of Brewing, Vol. 73, Issue 6, pp. 558-566.</br>
Description: Three aspects of head retention are calculated for 3 bottlings, (n1=n2=20,n3=19):
Head Formation, %Adhesion, and %Collapse Rate of foam.</br>
Readings made:</br>
A = @ 5secons: Top of beer foam</br>
B = @ 30seconds: level of the residual of beer below zero mark</br>
C = @ 240seconds: top of beer foam</br>
D = level of the center of the foam</br>
E = level of the residual beer</br>
%Adhesion = 100((A+B)-(A-C))/(A+B)</br>
%Collapse = 100((A+B)-(D+E))/(A+B)</br>
Tests: One-way ANOVA, independent samples t-test</br>

Name: ozone.csv</br>
Title: Thickness of Ozone Column in Dobson Units, Jan. Feb.</br>
Source: Laboratorium f_r Atmospharensphysic, Switzerland</br>
Description: In the following pairs the data represents the thickness of the ozone column in Dobson units: one milli-centimeter ozone at standard temperature and pressure.</br>
A = monthly mean thickness in January</br>
B = monthly mean thickness in February</br>
The data are paired by year for a random sample of 15 years.</br>
Tests: Paired t-test</br>
 
Name: reddye40.csv</br></br>
Title: Red Dye 40 and Cancer in Mice</br>
Source: Journal Natl. Cancer Inst., Vol. 66, p 197-212</br>
Description: S.W. Laagakos and F. Mosteller of Harvard University fed mice different doses of red dye number 40 and recorded the time of death in weeks. Results for female mice, dosage and time of death are shown in the data</br>
X1 = time of death for control group</br>
X2 = time of death for group with low dosage</br>
X3 = time of death for group with medium dosage</br>
X4 = time of death for group with high dosage</br>
Tests: One Way Anova</br>

Name cricketchirps.csv</br>
Title: Cricket Chirps vs. Temperature</br>
Source: The Song of Insects by Dr.G.W. Pierce, Harvard College Press</br>
Description: In the following data</br>
X = chirps/sec for the striped ground cricket</br>
Y = temperature in degrees Fahrenheit</br>
Tests: linear regression, rho t-test</br>

Name: ufo.csv</br>
Title: UFO Sightings</br>
Source: www.uforesearchdb.com</br>
Description: Description: UFO sightings in the US (3437 events). Date, Shape, Location, State, Country, and  Source.</br>
Variables/Labels</br>
Event.Date</br>
Shape</br>
Location</br>
State</br>
Country</br> 
Source (NUFORC = Nationaol UFO Reporting Center, MUFON = Mutual UFO Network)</br>
USA (1=USA, 0=Not USA)</br>
Test: Chi Square (Categorical/Nominal Data)</br>

Name: appleroots.csv </br>
Title: Apple Orchard Experiment </br>
Source: S.C. Pearce, University of Kent at Canterbury, England </br>
Description: Five types of root-stock were used in an apple orchard grafting experiment. The following data represent the extension growth (cm) after four years. </br>
X1 = extension growth for type I </br>
X2 = extension growth for type II </br>
X3 = extension growth for type III </br>
X4 = extension growth for type IV </br>
X5 = extension growth for type V </br>

Name: foxrabies.csv</br>
Title: Fox Rabies</br>
Source: Sayers, B., Medical Informatics, Vol. 2, 11-34</br>
Description: The data represent the number of cases of red fox rabies for a random sample of 16 areas in each of two different regions of southern Germany.</br>

Online data sources:</br>
http://www.stat.ufl.edu/~winner/datasets.html</br>
http://college.cengage.com/mathematics/brase/understandable_statistics/7e/students/datasets/tvds/frames/frame.html</br>
http://www.statsci.org/data/index.html</br>
http://www.kaggle.com</br>

Name: titanic.csv</br>
Features</br>
survival - Survival (0 = No; 1 = Yes)</br>
class - Passenger Class (1 = 1st; 2 = 2nd; 3 = 3rd)</br>
name - Name</br>
sex - Sex</br>
age - Age</br>
sibsp - Number of Siblings/Spouses Aboard</br>
parch - Number of Parents/Children Aboard</br>
ticket - Ticket Number</br>
fare - Passenger Fare</br>
cabin - Cabin</br>
embarked - Port of Embarkation (C = Cherbourg; Q = Queenstown; S = Southampton)</br>
boat - Lifeboat (if survived)</br>
body - Body number (if did not survive and body was recovered)</br>
