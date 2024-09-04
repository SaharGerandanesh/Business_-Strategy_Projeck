# Projeck_Age_Salary
Affärsstrategi: Genom att förstå vilka demografiska grupper som är mest benägna att göra köp kan företag optimera sina resurser genom att fokusera marknadsföring och kampanjer på dessa segment. Detta kan leda till högre konverteringsgrader och bättre avkastning på investeringar.
Variabler:

User ID: Unikt identifieringsnummer för varje användare.
Gender: Kön på användaren (Male/Female).
Age: Användarens ålder i år.
EstimatedSalary: Användarens uppskattade årliga lön i lokal valuta.
Purchased: Binar variabel som indikerar om användaren har gjort ett köp (1) eller inte (0).
2. Exploratory Data Analysis (EDA)
Fördelning av variabler
Ålder: Medelåldern är 37,7 år, och fördelningen av ålder sträcker sig från 18 till 60 år. Det verkar finnas en spridning över hela arbetsåldern.
EstimatedSalary: Medellönen i datasetet är 69 742,50, med en standardavvikelse på cirka 34 097. Lönerna varierar från 15 000 till 150 000, vilket indikerar en stor variation i ekonomiska förhållanden bland användarna.
Könsfördelning: Detta dataset innehåller både manliga och kvinnliga användare, men kön är en kategorisk variabel och kräver specifik analys för att se om det finns skillnader i andra variabler baserat på kön.
Relationer mellan variabler
Korrelation mellan ålder och EstimatedSalary: Scatter plots kan användas för att undersöka om det finns något tydligt samband mellan ålder och lön. Inledningsvis verkar det som att det inte finns någon stark korrelation mellan dessa två variabler.
Köpbeslut (Purchased) mot andra variabler: Genom att titta på hur variablerna Ålder och EstimatedSalary relaterar till köpbeslutet (Purchased), kan vi försöka identifiera om det finns vissa ålders- eller lönegrupper som är mer benägna att göra ett köp.
3. Unsupervised Machine Learning
K-means clustering:

Syfte: Utföra klusteranalys för att se om det finns dolda grupper i data som kanske korrelerar med köpbeslutet (Purchased).
Val av kluster: Vi kan börja med att använda 3-4 kluster för att se hur användarna kan grupperas baserat på ålder och EstimatedSalary.
Resultat: Efter att ha kört K-means klustring kan vi undersöka om vissa kluster visar en högre frekvens av köpbeslut (Purchased = 1). Detta kan ge insikter i vilka demografiska grupper (baserat på ålder och inkomst) som är mest benägna att göra köp.
4. Presentation av resultat
Visualisering av EDA-resultat:
Scatter Plots: Visualisera fördelningen av ålder och EstimatedSalary i relation till köpbeslutet.
Box Plots: Undersök hur EstimatedSalary och Age varierar för de som har gjort ett köp (Purchased = 1) jämfört med de som inte har gjort ett köp.
Klusteranalysens resultat:
Kluster Visualisering: Scatter plot med klusterfärgning visar hur användarna grupperas. Vi kan också överlägga köpbeslutet för att se om vissa kluster har en högre andel köp.
5. Databerättelse
Denna analys visar hur vi kan identifiera potentiella kundsegment baserat på demografi och inkomstdata. Genom att använda K-means klustring kunde vi identifiera grupper av användare som har liknande ålder och EstimatedSalary. Resultaten antyder att vissa av dessa grupper har en högre sannolikhet att göra köp, vilket kan vara värdefullt för att rikta marknadsföring och erbjudanden.

Key Takeaways:
Segmentering: Vi kunde identifiera grupper med liknande ålder och EstimatedSalary. En av dessa grupper kan ha en högre sannolikhet att köpa, vilket gör dem till ett attraktivt mål för marknadsföringsinsatser.
Affärsstrategi: Genom att förstå vilka demografiska grupper som är mest benägna att göra köp kan företag optimera sina resurser genom att fokusera marknadsföring och kampanjer på dessa segment. Detta kan leda till högre konverteringsgrader och bättre avkastning på investeringar.
Affärsnytta: Denna typ av analys kan hjälpa företag att bättre förstå sina kundbaser, identifiera nya marknadsmöjligheter och förbättra precisionen i sina marknadsföringskampanjer, vilket slutligen kan leda till ökad försäljning och kundnöjdhet.
