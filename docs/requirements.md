# Requirements

## Functional requirements (what the system must DO)
1. The system shall allow users to upload a static image of a cat for breed classification.  
2. The system shall classify the uploaded image and display the predicted cat breed along with a visual confidence score.  
3. The system shall retrieve and display historical information and general care guides corresponding to the classified breed. 
4. The system shall allow users to upload a targeted close-up image of a cat's skin abnormality for screening.  
5. The system shall classify selected skin conditions (e.g., fungal, flea infestation, scabies) and display preliminary non-prescriptive care guidance.
6. The system shall display a non-medical advisory disclaimer stating that predictions are preliminary and do not constitute a confirmed veterinary diagnosis. 

## Non-functional requirements (how the system must PERFORM)
1. The system shall process an uploaded image and return classification results within 5.0 seconds or less.  
2. The computer vision model shall achieve at least 85.0% accuracy on test images. 
3. The system shall accept only .jpg, .jpeg, and .png picture files under 10 MB in size.