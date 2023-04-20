# X.CarMechanic
🚗Get instant quotes from repair manual and visual tips in AR camera with mobile app powered by GPT and vision segmentation!🛠️

The application detects the OBD error code from the car tester's camera and provides the user with a quote from the car repair manual. It then guides the user, who is a professional car mechanic, through the troubleshooting process step-by-step, including recommendations on which components to replace and what to check. To aid in the process, the application uses an AR overlay to indicate specific components within the camera's view.




The solution will involve using Android JetPack/SwiftUI for native clients and a FastAPI Python server that leverages OpenAI through LangChain. The application will be augmented with a relevant embedding from car repair manuals stored in Weaviate vector database and a custom vision model trained on annotated car repair videos.




