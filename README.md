# Queue Management System 🎛️

A Java desktop application that simulates real-time queue management for servicing clients. The system allows you to configure simulation parameters and choose different allocation strategies to optimize client servicing.

## 🚀 Features

- Real-time simulation of client queues
- Configurable number of clients, queues, arrival times, and service times
- Two dynamic allocation strategies:
  - **Shortest Queue**
  - **Shortest Time**
- Graphical representation of queues and waiting clients
- Displays average waiting time, service time, and peak hours
- Input validation to ensure accurate simulation data

## 🛠️ Technologies Used

- Java (Swing for GUI)
- OOP, Multithreading
- Maven (project build and dependency management)
- IntelliJ IDEA


## 📂 Project Structure

```
Queue-Management-System/ 
├── src/ 
│ ├── main/ 
│ │ ├── java/ 
│ │ │ ├── BusinessLogic/ # Queue management, strategies 
│ │ │ ├── GUI/ # UI and controller 
│ │ │ └── Models/ # Client, Queue definitions 
│ ├── test/ # Unit tests 
├── resources/ # Images (open.png, close.png, stickman.png) 
├── target/ # Maven build output (ignored) 
├── .gitignore # Git ignore rules 
├── LICENSE # Project license (MIT) 
├── pom.xml # Maven configuration 
├── README.md # Project documentation
```

## ⚙️ How to Run the Project

1. Clone the repository:
   ```
   git clone https://github.com/somodidenise/Queue-Management-System.git
   ```
2. Open the project in IntelliJ IDEA or another Java IDE.
3. Build the project using Maven:
```
mvn clean install
```
4. Run the Main class from the GUI package to launch the application.

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.