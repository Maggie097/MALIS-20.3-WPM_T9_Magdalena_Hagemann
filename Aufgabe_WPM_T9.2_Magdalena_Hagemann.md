Aufgabe MALIS 20.3 
WPM_T9.2: Data Science / Data Librarianship / IT-Praxis
Autorin: Magdalena Hagemann
Datum: 05.06.2021

**Binäre logistische Regression mit Python**

Im Zentrum der hier zu bearbeitenden Aufgabe steht die Durchführung einer binären logistischen Regression mit der Programmiersprache Python. Der Hintergrund zu der geplanten Analyse soll im Folgenden erläutert werden:

Im Rahmen des GestDiab-Registers des Instituts winDiab (Forschungsinstitut der niedergelassenen Diabetologen) werden Daten von schwangeren Frauen mit Gestationsdiabetes sowie Typ-1- und Typ-2-Diabetes erfasst und verarbeitet. Ziel ist es, mehr über die Versorgungslage dieser Frauen in den diabetologischen Praxen zu erfahren. Hierfür werden die Daten regelmäßig ausgewertet sowie nach bestimmten Gesichtspunkten analysiert. 

In dieser Aufgabe soll ein reduzierter Datensatz aus dem Register (bestehend aus den Daten von 100 Patientinnen) dazu verwendet werden, eine Schlussfolgerung aus vorhandenen Daten abzuleiten, mit dem Ziel, Anhaltspunkte zur Optimierung der Behandlung und Versorgung der Patientinnen zu gewinnen. Konkret geht es dabei darum, aus vier verschiedenen Parametern, welche von Frauen mit Gestationsdiabetes bekannt sind, die Wahrscheinlichkeit dafür abzuleiten, ob eine Insulintherapie notwendig sein wird oder nicht.

Bei den eben genannten Parametern handelt es sich um das jeweilige Alter der Frauen, den Nüchternglukose-Wert, den Body-Mass-Index (BMI) und die Gravida, also die Häufigkeit der bisherigen Schwangerschaften. 

Auf die Durchführung der logistischen Regressionsanalyse lässt sich das Ganze folgendermaßen übertragen: Die oben genannten Parameter stellen unabhängige Variablen dar. Diese sollen in Zusammenhang gebracht werden mit einer abhängigen Variable, die aus zwei Kategorien besteht, nämlich: Insulintherapie: ja, Insulintherapie: nein, wobei „ja“ den Wert 1 und „nein“ den Wert 0 erhält. Ziel ist es, die Wahrscheinlichkeit dafür zu schätzen, ob die abhängige Variable den Wert 1, also „ja“ oder den Wert 0, also „nein“ erhält.

Bei den unabhängigen Variablen in diesem Beispiel (Alter, Nüchternglukose-Wert, BMI und Gravida) handelt es sich um quantitative Variablen. Das bedeutet, dass sie aus Zahlenwerten bestehen. Die abhängige Variable ist zwar kategorial (ja/nein), wird jedoch – wie oben beschrieben – umcodiert in die Werte 0 und 1.

Ziel ist es, herauszufinden, wie die Höhe der Werte der unabhängigen Variablen mit der Wahrscheinlichkeit für den Wert 1 bzw. 0 zusammenhängt. Steigt die Wahrscheinlichkeit, eine Insulintherapie zu benötigen, mit den steigenden Werten der Variablen (also mit erhöhtem Alter, erhöhtem Nüchternglukose-Wert, erhöhtem BMI und der Häufigkeit der Schwangerschaften) an?  

Diese Frage soll mittels Python beantwortet und am Ende auch grafisch dargestellt werden. Dabei wird zunächst der Datensatz, welcher als Excel-Tabelle vorliegt, in ein Git-Repositorium hochgeladen. Diese Tabelle wird daraufhin in ein Jupyter Notebook importiert, in welchem dann die für die logistische Regression benötigten Skripte erstellt werden. Die Anwendung der Bibliothek Pandas ist in diesem Beispiel besonders hilfreich, da Pandas die Analyse von Daten erleichtert. 
