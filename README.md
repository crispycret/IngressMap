# Ingress Monitoring System

## Project Goal
The Ingress Monitoring System aims to provide a comprehensive solution for recording and analyzing ingress readings from customer homes in an HFC network. By utilizing this system, service technicians can identify problematic homes, perform regular network cleanings, and ultimately improve the overall performance of the broadband service.

## Technologies Involved
- **Frontend**: React.js
  - User interface for submitting ingress readings manually and uploading files from the Viavi ONX 650 meter.
  - Interactive map for visualizing ingress reports with filtering options.
  
- **Backend**: Python (Flask/Django)
  - API for user authentication and data management.
  - Database for storing ingress readings and user information.

- **Mapping**: Leaflet.js or Google Maps API
  - Displaying ingress data on a map with longitude, latitude coordinates, and addresses.

## How to Use
1. **Installation**: Clone the repository and install the necessary dependencies for both the frontend and backend.
2. **Frontend**: Start the React application to access the user interface for submitting ingress readings.
3. **Backend**: Run the Python API to handle authentication and data storage.
4. **Map Visualization**: Use the map feature to filter and view ingress reports based on frequency and severity.

## Contributing
Contributions are welcome! Please submit a pull request or open an issue for any suggestions or improvements.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.