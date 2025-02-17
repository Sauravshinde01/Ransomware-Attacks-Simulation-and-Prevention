
# Ransomware Attacks Simulation and Prevention

This project simulates ransomware attacks and demonstrates prevention techniques using Python.

## Project Structure
- **decryption.py**: Handles decryption of encrypted files.
- **mitipsutil.py**: Utility functions for managing encryption keys.
- **monitorwithscapy.py**: Network traffic monitoring using Scapy.
- **pyinotifydemo.py**: Monitors file system changes with Pyinotify.
- **securitypatch.py**: Applies security patches to prevent attacks.
- **sendemail.py**: Sends email notifications in case of detected threats.
- **watchdogdemo.py**: File monitoring using Watchdog.

## Requirements
- Python 3.x
- Libraries: `scapy`, `pyinotify`, `watchdog`, `smtplib`

## Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/Sauravshinde01/Ransomware-Attacks-Simulation-and-Prevention
   ```
2. Install dependencies:
   ```bash
   pip install scapy watchdog pyinotify
   ```
3. Run individual scripts for respective functionalities.

## Usage
- Use `monitorwithscapy.py` for monitoring network traffic.
- Execute `securitypatch.py` to apply security patches.
- Run `sendemail.py` for sending alerts.

## Project Motivation
This project was inspired by the increasing threat of ransomware attacks in modern cybersecurity. It was designed to understand the lifecycle of ransomware and develop proactive prevention measures.

## Challenges Overcome
Faced challenges in ensuring real-time monitoring without performance degradation and implemented efficient encryption techniques while maintaining data integrity.

## Future Enhancements
- Integration with SIEM tools for centralized threat monitoring.
- Adding more advanced ransomware attack vectors.
- Implementing machine learning models for anomaly detection.

## Contributions
Feel free to fork and submit pull requests.

## License
This project is licensed under the MIT License.

## Contact
Saurav Shinde - [LinkedIn](https://www.linkedin.com/in/sauravshinde-cyber)
