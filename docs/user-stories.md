# User Stories

1. As a cat owner, I want to scan localized skin patches on my cat using my smartphone, so that I can catch early signs of skin infections and receive preliminary care guidance. (FR3)
    Acceptance criteria:
    - Uploading a close-up photo of an affected skin area highlights suspected lesion boundaries using visual heatmaps or bounding boxes.
    - The diagnostic output displays suspected skin conditions ranked by probability score alongside a preliminary risk rating (e.g., Normal, Mild, High Risk).
2. As a veterinary practitioner, I want clients to share an exported diagnostic PDF summary report, so that I can review their cat's visual history and preliminary risk scores before an in-person consultation. (FR5)
    Acceptance criteria:
    - Clicking "Export Report" compiles the uploaded image, breed result, and skin condition risk levels into a standardized, downloadable PDF.
    - The exported report contains a clear medical disclaimer stating that AI findings are preliminary visual screening indicators, not final clinical diagnoses.
3. As an animal shelter staff member, I want to upload photos of newly rescued stray cats, so that I can automatically classify their breed and screen them for contagious skin conditions like ringworm during intake. (FR2)
    Acceptance criteria:
    - Uploading a rescue cat's picture returns its predicted breed and top confidence scores within 3 seconds.
    - If a contagious skin condition (e.g., ringworm) is flagged at high probability, the system displays an instant quarantine recommendation alert.