# CarePulse

## A healthcare patient management application that allows patients to easily register, book, and manage their appointments with doctors. Features administrative tools for scheduling, confirming, and canceling appointments, along with SMS notifications.



### Features 
- Patients can schedule appointments with doctors at their convenience and can book multiple appointments.
- Administrators can efficiently view and handle all scheduled appointments.
- Patients receive SMS notifications to confirm their appointment details.
- The application works seamlessly on all device types and screen sizes.

![image](https://github.com/user-attachments/assets/67cd694e-4a73-419b-9c22-ca07b5fb5d43)




Checkout the app [here](https://carepulse-azure.vercel.app/)

### Techstack 
![Next JS](https://img.shields.io/badge/Next-black?style=for-the-badge&logo=next.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Shadcn](https://img.shields.io/badge/shadcn/ui-000000.svg?style=for-the-badge&logo=shadcn/ui&logoColor=white)
![Appwrite](https://img.shields.io/badge/Appwrite-FD366E.svg?style=for-the-badge&logo=Appwrite&logoColor=white)


### Quick start
#### Prerequisites

Make sure you have the following installed on your machine:
- Git
- Node.js
- npm

#### Cloning the Repository
```
git clone https://github.com/Vijaychandra-Govindapalle/Carepulse
cd Carepulse
```
#### Installation
```
npm install
```

#### Set Up Environment Variables

Create a new file named .env in the root of your project and add the following content:

```
#APPWRITE
NEXT_PUBLIC_ENDPOINT=https://cloud.appwrite.io/v1
PROJECT_ID=
API_KEY=
DATABASE_ID=
PATIENT_COLLECTION_ID=
APPOINTMENT_COLLECTION_ID=
NEXT_PUBLIC_BUCKET_ID=

NEXT_PUBLIC_ADMIN_PASSKEY=111111
```
Replace the placeholder values with your actual Appwrite credentials. You can obtain these credentials by signing up on the [Appwrite](https://appwrite.io/) website.

#### Running the Project
```
npm run dev
```



