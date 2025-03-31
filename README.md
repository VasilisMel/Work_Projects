# Professional projects
<p align="center">
  <img src="https://github.com/VasilisMel/Work_Projects/blob/media/DEH_gif.gif" width="100" height="100" alt="animated" />
</p>
<h3 align="center"> In this repository, an overview of professional projects is provided along with their summary respectively.
</h3>

## EV4EU O-V2X-MP platform (GR Demo)

The Open Vehicle-to-Everything Management Platform (O-V2X-MP) is developed as part of the European EV4EU project, serving as a comprehensive solution for EV charging infrastructure management with grid integration capabilities. Led by PPC in the Greek demonstration, this platform bridges electric vehicles, charging stations, and distribution systems.

### Architecture & Technologies

- **Backend**: Python-based implementation using Django, Sanic, and Celery frameworks
- **Frontend**: User-friendly dashboard built with Node.js and Vue.js
- **Security**: Multi-layered protection with OAuth 2.0, Keycloak, and JWT authentication
- **Deployment**: Containerized microservices ensuring scalability and maintainability

### Key Features

- **For Operators**:
  - Real-time monitoring of charging stations
  - Smart charging algorithms (BUC 4 and BUC 5)
  - Dynamic tariff management
  - Fair load distribution

- **For EV Users**:
  - Charging station location services
  - Session management
  - Multiple authentication methods
  - Real-time status updates

- **Grid Integration**:
  - DSO Support System connections
  - Dynamic capacity adjustment
  - Implementation of demand response services

### Hardware Integration

The platform has been successfully tested with Autel MaxiCharger AC Wallbox charging stations with OCPP 1.6J protocol support. Future developments include OCPP 2.0.1 and 2.1 integration for bi-directional charging capabilities.

The project's [Demo sample](https://mega.nz/file/pSAyzaQS#0HwqEria7IRogUiKAROfb9nNk1Prvozk23ieR7GuKRI)

[<img src="https://github.com/VasilisMel/Work_Projects/blob/media/ov2xmp_gif.gif"  />](https://mega.nz/file/pSAyzaQS#0HwqEria7IRogUiKAROfb9nNk1Prvozk23ieR7GuKRI "Demo sample here")

## My_Consumption_Planner (GUI)
A Graphical User Interface (GUI) application was created to simulate and illustrate in a more palpable manner how the consumers will benefit from the methodology. This application offers users a range of choices, including default consumption, frequency usage tips, device replacement tips, and a combination of frequency usage tips and device replacement tips for each device available for review. Additionally, the program provides fixed results that are based on all consumer devices which a specific suggestion tip was followed at a time. Thus, apart from the original and custom plan charts, an additional set of the three proposed suggestions is provided.

This consumer-based application can grant the consumer any meaningful information. The system provides the previous consumption period the consumer has contracted along with the type of consumption (Daily/Nightly) contract. Next, a set of household-based information is depicted that informs the consumer the brief statues of the house type, the number of people living inside, the members age, the heating system etc. Apart from the informative sets the application provides, there is also the selection part where each device with consumption review availability can be selected from 4 different consumption plans (including the default one) for the next consumption period. After the consumer has selected every consumption plan for every device of his choice, he will be able to observe the amount of money he will pay for the next consumption period. Moreover, in this consumption chart, there is another chart that reviews the consumer's consumption behavior based on the consumption plan he selected with a bar from 0 to 7 that also matches the European Energy Labels which are used to review the devices of the household. 

Apart from the device with review availability, in the consumption plan, the consumption of the non-consumption review-available devices is forcedly added in the chart. There is also a last layer of information that refers to the depreciation analysis of the candidate devices and the exact time it needs to completely depreciate them. Additional charts were added that compare the default consumption behavior with the rest consumption plans in consumption behavior review and in energy bill.

The project's [Video sample](https://mega.nz/file/YLIw3CAA#Jb9T6s5lLF9N75X0iNv1tc1eXuO0C7aCEuXVDF9jAvA)

[<img src="https://github.com/VasilisMel/Work_Projects/assets/118008901/2d823d1e-7982-4b1d-9497-13984ae8a076"  />](https://mega.nz/file/YLIw3CAA#Jb9T6s5lLF9N75X0iNv1tc1eXuO0C7aCEuXVDF9jAvA "Video also here")
