---PASSWORD MANAGER---

THREE FACTOR AUTHENTICATION AND PASSWORD CLASSIFIER 


In the contemporary digital landscape, safeguarding sensitive information against unauthorized access demands robust security measures. This project proposes a comprehensive security framework that integrates three-factor authentication (3FA) with a password strength assessment system utilizing logistic regression. The three factors comprise something the user knows (password), something they possess (one-time password, OTP), and something they are (fingerprint biometrics). This multifaceted approach significantly fortifies authentication protocols, mitigating the vulnerabilities associated with single-factor authentication methods.
Furthermore, a machine learning-based password strength assessment system employing logistic regression is incorporated to evaluate the robustness of user passwords. By analyzing various parameters such as length, character diversity, and entropy, the system determines the strength of passwords and enforces stringent criteria to prevent the usage of weak passwords vulnerable to brute-force attacks or dictionary-based hacking techniques. Additionally, the system educates users about password best practices, fostering the creation of stronger and more resilient passwords.
The integration of 3FA with password strength assessment not only bolsters security but also enhances the user experience. With streamlined authentication processes and proactive password management, this framework addresses the evolving challenges of cybersecurity while prioritizing usability and convenience for end-users. Rigorous testing and evaluation will demonstrate the efficacy and practicality of the proposed security solution in safeguarding sensitive data across diverse digital platforms and applications.

Keyword:
Three-factor authentication, Password strength assessment, Logistic regression, Security framework, Cybersecurity, Authentication protocols, User authentication, Password management.

Introduction
 
2.1	  Problem Statement :

In today's digital landscape, ensuring robust security measures is paramount to protect sensitive information from unauthorized access. However, traditional authentication methods such as passwords alone are increasingly vulnerable to various cyber threats like brute-force attacks and phishing schemes. Additionally, users often create weak passwords that are easily guessable or susceptible to dictionary-based attacks, further compromising security.
To address these challenges, there is a need for a comprehensive security solution that combines multiple authentication factors with advanced password strength assessment techniques. Specifically, the project aims to develop a system that integrates three-factor authentication (3FA) with a machine learning-based password classifier using logistic regression.

2.2	Description of the system :

The system integrates three-factor authentication (3FA) with a machine learning-driven password classifier using logistic regression to enhance security. Users authenticate by providing a password, receiving a one-time password (OTP), and verifying their fingerprint. The password classifier analyzes password attributes and assigns strength scores, guiding users to create robust passwords. A user-friendly interface facilitates seamless authentication, while security measures including encryption safeguard sensitive data. Educational resources promote password best practices, ensuring users understand and adopt secure behaviors. Through these features, the system offers a comprehensive and user-centric solution to mitigate unauthorized access and data breaches.


2.3	  Limitation Of The System :

1. Biometric Constraints: The reliance on fingerprint biometrics for authentication may present limitations for users with certain physical conditions or occupations where fingerprint recognition is challenging or not feasible.
2. Dependency on External Factors: The effectiveness of the OTP factor relies on the availability and functionality of the token or mobile application generating the one-time passwords. Any disruptions or malfunctions in these external factors could hinder the authentication process.
3. False Positives/Negatives: The machine learning-based password classifier may occasionally misclassify passwords, leading to false positives (incorrectly identifying strong passwords as weak) or false negatives (failing to identify weak passwords). Continuous refinement and training of the classifier may mitigate but not entirely eliminate this risk.
4. User Compliance: The system's security effectiveness relies on users adhering to password best practices and actively engaging in multi-factor authentication. Resistance or negligence from users to follow recommended security guidelines could weaken the overall security posture.
5. Single Point of Failure: While multi-factor authentication reduces the risk of unauthorized access, it also introduces a single point of failure. If one authentication factor is compromised, such as the user's password, the entire authentication system's integrity may be compromised.
6. Resource Intensiveness: Implementing biometric authentication and machine learning-based password classification may require additional computational resources, potentially impacting system performance and scalability, especially in large-scale deployments.
7. Privacy Concerns: The storage and processing of biometric data raise privacy concerns, necessitating robust measures to secure and protect sensitive user information from unauthorized access or misuse.


2.4	Aim and Objective :

Aim: 

The aim of the project is to develop a comprehensive security solution that combines three-factor authentication (3FA) with a machine learning-based password classifier using logistic regression, thereby enhancing authentication security and user experience in digital environments.


Objectives:

1. Implement Three-Factor Authentication (3FA): Develop a robust authentication framework incorporating three authentication factors: something the user knows (password), something they possess (one-time password, OTP), and something they are (fingerprint biometrics).
2. Integrate Machine Learning-Based Password Classifier: Implement a password classifier using logistic regression to assess the strength of user passwords based on various metrics such as length, complexity, and uniqueness.
3. Enhance User Authentication Experience: Design and implement a user-friendly interface that guides users through the authentication process seamlessly, providing real-time feedback on password strength and facilitating the use of biometric authentication.
4. Educate Users on Password Best Practices: Provide educational resources and guidelines to promote password best practices among users, encouraging the creation of strong and secure passwords while avoiding common pitfalls.
5. Evaluate Security Efficacy: Conduct rigorous testing and evaluation of the implemented security solution to assess its effectiveness in mitigating unauthorized access and data breaches, considering factors such as false acceptance rate (FAR), false rejection rate (FRR), and user acceptance.
6. Address System Limitations: Identify and address potential limitations of the system, such as biometric constraints, false positives/negatives in password classification, and user compliance issues, through continuous refinement and optimization.
7. Ensure Privacy and Compliance: Implement robust measures to secure sensitive user data, including biometric information, and ensure compliance with relevant privacy regulations and standards.
8. Facilitate Scalability and Adaptability: Design the system to be scalable and adaptable to different digital environments and user requirements, considering factors such as resource intensiveness and deployment flexibility.
 
2.5	Project Motivation :

The motivation behind this project is fueled by the escalating cybersecurity threats prevalent in today's digital era. As instances of data breaches, identity theft, and unauthorized access continue to rise, there's an urgent need for fortified authentication mechanisms to shield sensitive information from exploitation. Traditional authentication methods, predominantly reliant on passwords, are increasingly susceptible to sophisticated attacks like brute-force attempts and phishing schemes. Thus, the project is driven by the necessity to bolster authentication protocols to counter these vulnerabilities effectively. Moreover, while enhancing security remains paramount, ensuring user convenience and usability is equally vital for widespread adoption. By striking a balance between security and user experience, the project aims to implement intuitive authentication processes and provide real-time feedback on password strength. Leveraging advancements in authentication technologies, such as biometrics and machine learning, presents an opportunity to develop more robust and user-friendly authentication solutions. Moreover, compliance with regulatory standards and data protection requirements underscores the project's commitment to safeguarding user privacy and confidentiality. Through education on security best practices and raising awareness about cybersecurity risks, the project seeks to empower users to proactively enhance their security posture. Ultimately, the project's overarching goal is to contribute to creating a safer and more secure digital environment by developing a comprehensive security solution that integrates multiple authentication factors and leverages advanced technologies.
 

3.	Description of the proposed work
 
3.1	

Number of modules

1. User Authentication Module:
- Handles user authentication processes, including password input, OTP generation and verification, and fingerprint biometric authentication.

2. Password Strength Assessment Module:
   - Implements the machine learning-based password classifier using logistic regression to evaluate password strength.
   - Analyzes password attributes and assigns strength scores to guide users in creating secure passwords.

3. User Interface (UI) Module:
   - Develops the user-friendly interface for authentication and password management.
   - Provides real-time feedback on password strength and guides users through the authentication process.

4. Security Module:
   - Implements encryption techniques to protect sensitive user data during transmission and storage.
   - Ensures compliance with privacy regulations and standards for handling biometric information and user data.

5. User Education Module:
   - Provides educational resources and guidelines to promote password best practices among users.
   - Offers security awareness training modules to enhance user understanding of cybersecurity risks and mitigation strategies.

6. Testing and Evaluation Module:
   - Conducts rigorous testing and evaluation of the implemented security solution to assess its effectiveness.

7. System Optimization Module:
- Identifies and addresses potential limitations of the system, such as biometric constraints and false positives/negatives in password classification.

 
3.2	Algorithm


1. Logistic Regression Algorithm:
   - Used in the password strength assessment module to classify passwords into categories based on their strength.
   - Logistic regression is employed to analyze various password attributes and assign strength scores.

2. Biometric Authentication Algorithm:
   - Implements algorithms for fingerprint recognition to verify the user's identity during biometric authentication.
   - This may involve techniques such as feature extraction, matching algorithms (e.g., minutiae matching), and decision-making algorithms for authentication.

3. Encryption Algorithms:
   - Utilized in the security module to encrypt sensitive user data during transmission and storage.
   - Common encryption algorithms include Advanced Encryption Standard (AES), Rivest-Shamir-Adleman (RSA), and hashing algorithms like SHA-256 for password storage.

4. OTP Generation Algorithm:
   - Generates one-time passwords (OTPs) for the second factor of authentication.
   - Algorithms for generating secure OTPs may involve random number generation and cryptographic techniques to ensure uniqueness and unpredictability.

5. Password Complexity Checking Algorithm:
- Used in conjunction with the password strength assessment module to evaluate password attributes such as length, character diversity, and entropy.
- Algorithms assess password complexity and adherence to best practices, such as avoiding common patterns and including a mix of alphanumeric characters and symbols.
 
3.3	

Working:

1. User Registration:
   - Users register by providing their credentials, including a password and fingerprint biometric data.
   - Biometric data is captured and stored securely in the system.

2. Authentication Process:
   - When a user attempts to log in, they are prompted to input their username and password.
   - The system verifies the correctness of the password using traditional authentication methods.
   - If the password is correct, the system prompts the user to provide their fingerprint for biometric authentication.

3. Biometric Authentication:
   - The system captures the user's fingerprint data through a biometric scanner or sensor.
   - The captured fingerprint data is compared against the stored biometric data to verify the user's identity.
   - If the fingerprint authentication is successful, the user is granted access to the system.

4. One-Time Password (OTP) Generation and Verification:
- In addition to the password and biometric authentication, the system generates a one-time password (OTP) and sends it to the user's registered device.
- The user receives the OTP and inputs it into the system.
  - The system verifies the correctness of the OTP to ensure possession of the registered device.

5. Password Strength Assessment:
   - During the password creation or modification process, the system analyzes the strength of the password using the machine learning-based password classifier.
- The classifier evaluates various attributes of the password, such as length, complexity, and uniqueness, and assigns a strength score.
- The system provides real-time feedback to the user on the strength of the password and encourages the creation of stronger passwords.

6. User Interaction and Feedback:
- Throughout the authentication and password management processes, the system interacts with the user through a user-friendly interface.
- The interface provides clear instructions and prompts for each authentication factor and offers feedback on password strength to guide users in creating secure passwords.

7. Security Measures:
- The system employs encryption techniques to protect sensitive user data, including passwords and biometric information, during transmission and storage.
- Regular security audits and updates are conducted to address emerging threats and vulnerabilities, ensuring the system remains resilient against cyber attacks.

 
3.   Coding

Machine Learning Code:
# Import the necessary Libraries
import pandas as pd
import matplotlib.pyplot as plt
from sklearn import metrics
# For text feature extraction
from sklearn.feature_extraction.text import TfidfVectorizer
# For creating a pipeline
from sklearn.pipeline import Pipeline
# Classifier Model (Logistic Regression)
from sklearn.linear_model import LogisticRegression
# Read the File
data = pd.read_csv('training.csv')
data.describe()
data.head()
# Features which are passwords
# Selecting all rows and coloumn 1 which are passwords of type 'string'.

features = data.values[:, 1].astype('str')
print(features)
# Labels which are strength of password
# Selecting all rows and last coloumn which are passwords strengths of type 'int'.

labels = data.values[:, -1].astype('int')
print(labels)
# Sequentially apply a list of transforms and a final estimator
classifier_model = Pipeline([
                ('tfidf', TfidfVectorizer(analyzer='char')),
                ('logisticRegression',LogisticRegression(multi_class='multinomial', solver='sag')),
])
# Fit the Model
classifier_model.fit(features, labels)
# Instead of splitting dataset into training and testing, we keep test dataset as seprate .csv file 
df= pd.read_csv('cleanpasswordlist.csv')
X = df.values[:, 1].astype('str')
y = df.values[:, -1].astype('int')
print('Testing Accuracy: ',classifier_model.score(X, y)100)
predictions = classifier_model.predict(X)
# Report the confusion matrix
from sklearn import metrics
print(metrics.confusion_matrix(y,predictions)) #first parameter x, second is y

# Print a classification report
print(metrics.classification_report(y,predictions))

#showing predication for 50 passwords as a sample
list=X[70:120]
predict=classifier_model.predict(list)

print(list)
print(predict)
# Taking sample of 50 passwords for ploting on Graph

x=features[100:150]
y=classifier_model.predict(x)
# Ploting graph

plt.scatter(x, y, color = 'red')

plt.title('Password vs Strength')
plt.xlabel('Password String')
plt.ylabel('Strength scale')
plt.show()
# Printing x coordinate
print(x)
# Printing y coordinate
print(y)
import joblib

# Fit the Model
classifier_model.fit(features, labels)

# Save the trained model as a pickle file
joblib.dump(classifier_model, 'password_strength_classifier_model1.pkl')

# Instead of splitting dataset into training and testing, we keep test dataset as seprate .csv file 
df = pd.read_csv('cleanpasswordlist.csv')
X = df.values[:, 1].astype('str')
y = df.values[:, -1].astype('int')

# Print the Testing Accuracy
print('Testing Accuracy: ', classifier_model.score(X, y)  100)

# Use the model to make predictions
predictions = classifier_model.predict(X)

# Report the confusion matrix
print(metrics.confusion_matrix(y, predictions))

# Print a classification report
print(metrics.classification_report(y, predictions))


Application Code:
package com.example.passwordmanager.ui.screens

import androidx.compose.foundation.ExperimentalFoundationApi
import androidx.compose.foundation.combinedClickable
import androidx.compose.foundation.layout.Box
import androidx.compose.foundation.layout.Column
import androidx.compose.foundation.layout.fillMaxSize
import androidx.compose.foundation.layout.fillMaxWidth
import androidx.compose.foundation.layout.padding
import androidx.compose.foundation.lazy.LazyColumn
import androidx.compose.foundation.lazy.items
import androidx.compose.material3.Button
import androidx.compose.material3.Card
import androidx.compose.material3.CircularProgressIndicator
import androidx.compose.material3.Text
import androidx.compose.runtime.Composable
import androidx.compose.runtime.getValue
import androidx.compose.runtime.mutableStateOf
import androidx.compose.runtime.remember
import androidx.compose.runtime.setValue
import androidx.compose.ui.Alignment
import androidx.compose.ui.Modifier
import androidx.compose.ui.text.style.TextAlign
import androidx.compose.ui.tooling.preview.Preview
import androidx.compose.ui.unit.dp
import com.example.passwordmanager.ui.Password
import com.example.passwordmanager.ui.dialogs.AddPasswordDialog
import com.example.passwordmanager.ui.dialogs.DeletePasswordDialog
import com.example.passwordmanager.ui.dialogs.ShowPasswordDialog
import com.example.passwordmanager.ui.theme.PasswordManagerTheme



@OptIn(ExperimentalFoundationApi::class)
@Composable
fun PasswordsListScreen(
    loading: Boolean,
    onSignOut: () -> Unit,
    onAddPassword: (String, String) -> Unit,
    passwords: List<Password>,
    onPrompt: (() -> Unit) -> Unit,
    onDeletePassword: (Password) -> Unit,
    modifier: Modifier = Modifier
) {
    var openShowPasswordDialog by remember { mutableStateOf(false) }
    var openAddPasswordDialog by remember { mutableStateOf(false) }
    var openDeletePasswordDialog by remember { mutableStateOf(false) }
    var selectedPassword by remember { mutableStateOf<Password?>(null) }

    Box(contentAlignment = Alignment.Center) {
        Column(horizontalAlignment = Alignment.CenterHorizontally) {
            Button(onClick = onSignOut) { Text(text = "Sign Out") }
            Button(onClick = { openAddPasswordDialog = true }) { Text(text = "Add Password") }
            Button(onClick = { "https://krishbari.github.io/password/" }) { Text(text = "Check Password Strength") }
            LazyColumn(
                modifier = modifier
                    .fillMaxSize()
                    .padding(8.dp),
                horizontalAlignment = Alignment.CenterHorizontally
            ) {
                items(passwords) { password ->
                    Card(
                        modifier = modifier
                            .padding(bottom = 8.dp)
                            .combinedClickable(
                                onClick = {
                                    selectedPassword = password
                                    onPrompt { openShowPasswordDialog = true }
                                },
                                onLongClick = {
                                    selectedPassword = password
                                    openDeletePasswordDialog = true
                                },
                            )
                    ) {
                        Text(
                            text = password.label,
                            modifier = modifier
                                .fillMaxWidth()
                                .padding(8.dp),
                            textAlign = TextAlign.Center
                        )
                    }
                }
            }
        }
        if (loading) {
            CircularProgressIndicator()
        }
    }
    if (openShowPasswordDialog) {
        ShowPasswordDialog(
            onDismiss = { openShowPasswordDialog = false },
            onConfirm = { openShowPasswordDialog = false },
            title = "${selectedPassword?.label}'s Password",
            text = selectedPassword?.text ?: "No password text found"
        )
    }
    if (openAddPasswordDialog) {
        AddPasswordDialog(
            onDismiss = { openAddPasswordDialog = false },
            onConfirm = { passwordName, passwordText ->
                openAddPasswordDialog = false
                onAddPassword(passwordName, passwordText)
            },
            title = "Add New Password"
        )
    }
    if (openDeletePasswordDialog) {
        DeletePasswordDialog(
            onDismiss = { openDeletePasswordDialog = false },
            onConfirm = {
                openDeletePasswordDialog = false
                onDeletePassword(selectedPassword!!)
            },
            title = "${selectedPassword?.label}'s Password"
        )
    }
}

@Preview(showBackground = true)
@Composable
fun PasswordsListPreview() {
    PasswordManagerTheme {
        PasswordsListScreen(
            loading = false,
            onSignOut = {},
            onAddPassword = { _, _ -> },
            passwords = listOf(
                Password(email = "1", label = "Gmail", text = "password1"),
                Password(email = "2", label = "Facebook", text = "password2")
            ),
            onPrompt = { },
            onDeletePassword = {}
        )
    }
}
 
4.1 Technology/Language/Development Tools/Hardware


1. Technology:
   - Android Studio: The primary technology for developing the mobile application.
   - Web Technologies: HTML, CSS, and JavaScript for developing the webpage hosting the machine learning component.

2. Programming Language:
   - Java/Kotlin: Java or Kotlin will be used for Android app development in Android Studio.

3. Development Tools:
   - Android Studio: Integrated Development Environment (IDE) for Android app development.
   - Text Editors: Text editors like Visual Studio Code or Sublime Text for editing HTML, CSS, and JavaScript files.
   - Machine Learning Libraries: machine learning algorithms in the web application.

4. Hardware:
- Development Devices: Android devices for testing and debugging the mobile application developed in Android Studio.
   - Web Hosting: A web server or cloud platform to host the webpage containing the machine learning component.
   - Biometric Scanner : If the Android device supports biometric authentication, it can be used for capturing fingerprint data during testing.
5.1	Conclusion
In conclusion, the proposed project of integrating three-factor authentication (3FA) with a machine learning-based password classifier serves as a significant step towards bolstering authentication security in digital environments. By leveraging technologies such as Android Studio for mobile application development and web technologies for the machine learning component, the project offers a comprehensive solution that prioritizes security, usability, and user education.

The system's architecture allows for seamless integration between the Android application and the machine learning model hosted on a webpage, facilitating efficient authentication processes and real-time feedback on password strength. Through rigorous testing and evaluation, the project aims to demonstrate the effectiveness of the implemented security solution in mitigating unauthorized access and data breaches while ensuring compliance with relevant privacy regulations and standards.



5.2	Future Scope

1. Advanced Biometric Authentication:
 Explore additional biometric modalities such as facial recognition or voice recognition to offer users more options for authentication, increasing flexibility and accessibility.

2. Integration with Additional Authentication Factors: 
Consider integrating additional authentication factors such as location-based authentication or behavioral biometrics to further enhance security and resilience against unauthorized access.

3. Continuous Improvement of Machine Learning Models: 
Continuously train and refine the machine learning-based password classifier to improve accuracy and effectiveness in assessing password strength, keeping pace with evolving cybersecurity threats and password trends.

4. Multi-Platform Support: 
Extend the application's support to other platforms such as iOS to cater to a broader user base and provide a consistent authentication experience across different devices and operating systems.

5. Enhanced User Education and Feedback Mechanisms: 
Develop interactive tutorials, quizzes, or gamified elements to engage users and reinforce password best practices, promoting a culture of security awareness and proactive risk mitigation.

6. Integration with Identity Management Systems: 
Integrate with identity management systems or single sign-on (SSO) solutions to streamline user authentication across multiple applications and platforms, enhancing user convenience while maintaining security.

7. API Development for Third-Party Integration: 
Develop APIs to allow third-party applications and services to integrate with the authentication system, enabling seamless authentication experiences across a diverse ecosystem of digital products and services.

8. Real-Time Threat Monitoring and Response: 
Implement real-time monitoring and anomaly detection mechanisms to identify and respond to suspicious authentication attempts or security breaches promptly, minimizing potential damage and ensuring continuous protection of user data.

9. Compliance with Emerging Standards and Regulations: 
Stay abreast of emerging cybersecurity standards and regulations, such as FIDO2 (Fast Identity Online) and GDPR (General Data Protection Regulation), and ensure compliance to maintain trust and credibility with users.

10. User Feedback and Iterative Development: 
Solicit feedback from users through surveys, usability testing, and analytics to identify pain points and areas for improvement, guiding iterative development cycles to enhance the system's effectiveness and user satisfaction over time.
								
 
