# 🏥 Hospital Management System (HMS)

This is a basic **Hospital Management System** built in Python using object-oriented principles. The system allows hospitals or clinics to manage **patients**, **doctors**, and **appointments** through a simple command-line interface.

---

## 📦 Project Structure

├── hms.ipynb # Contains class definitions and core logic

├── System.ipynb # Main program to interact with HMS via CLI

---

## 🔧 Core Components

### `human` (Base Class)
A parent class for common attributes:
- `id`
- `name`
- `age`
- `gender`

### `patient(human)`
Represents a patient.
- `__init__()`: Initialize patient details.
- `__str__()`: Printable string for patient info.

### `doctor(human)`
Represents a doctor.
- `__init__()`: Initialize doctor details including specialization.
- `__str__()`: Printable string for doctor info.

### `appointment`
Represents a medical appointment.
- `__init__()`: Patient ID, Doctor ID, and date/time of the appointment.
- `__str__()`: Printable string for appointment details.

### `Hospital_Management_System`
Main controller for managing patients, doctors, and appointments.

#### Key Methods:
- `addPatient()`: Add a new patient.
- `addDoctor()`: Add a new doctor.
- `setAppointment()`: Create a new appointment.
- `showpt()`: Display all patients.
- `showdr()`: Display all doctors.
- `showapp()`: Display all appointments.
- `export_patients_to_csv()`: Save patient data to CSV.
- `export_doctors_to_csv()`: Save doctor data to CSV.
- `export_appointments_to_csv()`: Save appointment data to CSV.

---

## 🧪 How It Works

The user interacts with the system through a simple CLI menu (in `System.ipynb`), where they can:
- Add or view patients/doctors
- Schedule and view appointments
- Export data to CSV


