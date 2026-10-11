# Vehicle Rental System
[Systems Programming Module]
<br>
<img width="309" height="167" alt="image" src="https://github.com/user-attachments/assets/6e9f5ef8-8a15-44fa-a48c-d56340b57c26" />
<img width="272" height="216" alt="image" src="https://github.com/user-attachments/assets/3bd35059-54e2-4f4b-9e29-4f005a65813d" />
<img width="216" height="193" alt="image" src="https://github.com/user-attachments/assets/f31aa807-6ad8-4037-b04b-88d29a864b93" />
<img width="1265" height="365" alt="image" src="https://github.com/user-attachments/assets/72233704-34f4-4447-adc3-c7bbb3a7b78b" />

## 🎓 About This Project
> This is my systems programming module **assignment** project for Software Engineering at Sheffield Hallam University (2024). It was developed to meet a marking criteria, so it is **not at a production-level standard**.

🫟 **Problem:** The objective of this assignment was to choose a real-world system and reduce it to a console-based application ensuring to implement all of the OOP (Object-Oriented-Programming) principles. Given the complexity of a vehicle rental website, turning it into a console app would cover all OOP areas plus more, and despite the difficult development proved to be a successful assignment project.

🚪 **Approach:** Built with C# and .NET in Visual Studio. Implementing an _abstract_ base vehicle class with 3 sub-classes (Cars, Vans, Motorcycles), each with its own constructor to create a new vehicle object with its own properties on-top of the ones it _inherited_. Getters and setter methods are utilised for every property, base and inherited, for access to the objects due to the protected and private status of the class fields, _encapsulation_. _Polymorphic_ functions are implemented primarily for the reading and writing of vehicle data to the binary file,  

### ✨ Features
- Register an account and login, not required to view vehicles.
- Navigate and view multiple pages of different types of vehicles (cars, vans, motorcycles).
- Upload vehicle details to be put up for rent.
- Rent & Return vehicles (Fake).
- Access the system via the command line. 

---
🚦 **Status:** Working, though the application is very basic and should not be used for real-world purposes.

---
### 🛠️ Tech Stack
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=for-the-badge&logo=csharp&logoColor=white)
<br>
![.Net](https://img.shields.io/badge/.NET-%235C2D91.svg?style=for-the-badge&logo=.net&logoColor=white)
<br>
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white)
![NuGet](https://img.shields.io/badge/nuget-%23004880.svg?style=for-the-badge&logo=nuget&logoColor=white)

---
## 📦 Setup
### 🚀 Installation
```bash
git clone https://github.com/TZevs/Vehicle_Rental_System.git
```
### Usage
1. Open folder `Vehicle_Rental_System/VehicleRentalApp` in Visual Studio.
2. Double Click the `VehicleRentalApp.sln` in the Solution Explorer on the right-hand side.
3. Press Run.

**OR**
1. Open folder `Vehicle_Rental_System/VehicleRentalApp` in Files.
2. Double Click the `VehicleRentalApp.sln` (Opens Visual Studio).
3. Press Run.

**OR**
```bash
cd Vehicle_Rental_System/VehicleRentalApp/bin/Debug/net8.0
dotnet VehicleRentalApp.dll <cmd_name>     # --help to get all cmds
```

---
## 🔍 Known Issues & Improvements to be Made
- **Console Limited:** implementing a full frontend for better accessibility would be the first step, using Windows Forms or ASP.NET, etc.
- **No Verification:** have access to an api that stores real vehicle data to ensure that someone enters their own.

---
## 🤝 Credits
This project was created as a module assignment for my degree at Sheffield Hallam University.

## 📄 Licence
This project is licensed under the MIT License.
