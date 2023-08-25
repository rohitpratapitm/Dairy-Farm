<h3>Entity Relationship Diagram</h3>
<a href="https://lucid.app/lucidchart/7b7f6c42-753b-487d-a7dc-ef7408d6c149/edit?viewport_loc=-560%2C-32%2C3072%2C1580%2C0_0&invitationId=inv_7f22d004-ebcb-4beb-987f-53b8061281bf">Entity Relationship Diagram</a>

## Cow:

* UIN: String
* type: String (FK)
* pictureUrl: String
* dob: Date
* status: Pregnant | Ready For Insemination | In Milking | Sick
* nextVaccinationDate: Date

Cow Category:
* Id: String
* name: String
* description: String

Vaccination History:
* Id: String
* cowId: String (ForeignKey)
* vaccinationId: String (ForeignKey)
* dateOfVaccination: Date

Vaccination:
* Id: string
* name: string


Breeding History:
* Id: String
* cowId (foreign key): String
* inseminatedDate: Date
* Sire: (foreign key): String
* deliveryDate: Date
* noOfCalves: number


Lactation:
* Id: String
* cowId: String (foreign Key)
* MorningQuantity: number
* EveningQuantity: number
* date: Date

User:
* id: String
* name: String
* role: Admin | Manager | Supervisor | Worker 
* dob: Date

Fodder:
* Id: string
* type: Alfalfa | Timothy Grass | Corn Silage | Haylage
* quantityAvailable: number
* harvestingSeason: String
* storageConditions: Silo | Hay Barn | Dry Storage
* cost: currency
* qualityGrade: String
* usage: Daily Ration | Special Feed | Seasonal Feed
* expirationDate: Date
* deliverySchedule: date
* organic: boolean

Crop:
* id: String
* sowingDate: Date
* expectedHarvestDate: Date
* healthStatus: String
* quantityExpected: number
