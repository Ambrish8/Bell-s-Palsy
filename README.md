# Bell-s-Palsy
Bell’s Palsy is a neurological disorder that causes sudden, temporary weakness
or paralysis of the facial muscles, impacting one side of the face. Early and
accurate severity detection of Bell’s Palsy is crucial for effective treatment and
recovery. This project aims to develop an automated severity detection system
focusing on key facial features—eyebrows, eyes, and mouth—using deep
learning techniques.
We utilize ResNet, a powerful deep convolutional neural network (CNN), to
classify Bell’s Palsy severity into four categories: mild, moderate, moderate
severe, and severe. The dataset consists of annotated facial images,
preprocessed with data augmentation techniques such as rotation, zooming, and
flipping to improve model robustness. The dataset is split into training,
validation, and testing sets for effective model training and evaluation.
The model is fine-tuned using transfer learning, leveraging a pre-trained
ResNet model while modifying its classifier to suit our classification task. The
training process is carried out on Google Colab, using an Adam optimizer and
cross-entropy loss function. The model’s performance is evaluated using
accuracy and loss metrics on the test dataset.
By automating the severity assessment of Bell’s Palsy, this project offers a fast,
accurate, and scalable solution to assist medical professionals in early diagnosis
and treatment planning. The system can potentially be integrated into mobile
applications or telemedicine platforms, improving healthcare accessibility for
patients in remote areas.
