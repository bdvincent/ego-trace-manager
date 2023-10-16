# ego-trace-manager
Realized the design and development of a functional safety application system. The main framework is built using C#, using .Net version 4.6, and using SQLite database for lightweight use. In order to achieve rapid response, C++ is used to load the face anti-spoofing model combined with the above algorithm structure design and optimized through the multiple data enhancement method framework using frugally-deep, and the face authenticity verification method is called across platforms. Finally, the high-speed features of the C++ language can be used , to achieve fast loading and calling of models. The application contains eight common security-related operation modules, including user login and registration, face recognition matching, face authenticity verification, information encryption and decryption, document information management, digital watermark addition and extraction, computer U disk information management, port scanning, etc. Function. Among them, the face anti-spoofing algorithm is integrated into the user login and registration stage, and is combined with face recognition to perform anti-spoofing verification of the logged-in face and username and password verification, forming the multiple security mechanisms of this application. In addition, a permission classification mechanism is designed to ensure the effect of logged-in users using all functions and non-logged-in verification users using restricted functions. On this basis, some advanced operations are also implemented, such as form animation, cross-form parameter transfer, dynamic transparency of controls and other effects, which can provide a full range of security services for users with multiple identities.
