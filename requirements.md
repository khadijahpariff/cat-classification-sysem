# Requirements

## Functional requirements (what the system must DO)
1. The system shall allow users to upload or capture clear images of a cat via the web or mobile user interface.
2. The system shall classify the cat’s breed using a visual feature model and display the predicted breed along with top matching confidence percentages.
3. The system shall analyze uploaded skin or coat images to detect localized feline dermatological conditions, such as ringworm, flea allergy dermatitis, and hair loss.
4. The system shall display a diagnostic preliminary risk rating (e.g., Normal, Mild, High Risk) accompanied by standard veterinary care advice and disclaimers.
5. The system shall allow users to export the breed classification and skin diagnostic findings as a downloadable PDF summary report. 

## Non-functional requirements (how the system must PERFORM)
1. The system shall complete visual inference and display classification and skin diagnostic results within 3 seconds of image submission under normal network conditions.
2. The computer vision model shall achieve a minimum top-1 classification accuracy of 85% on standard validation datasets for cat breed and skin condition identification.
3. The system shall secure user profile data and uploaded images in transit using TLS 1.3 network encryption protocols.
