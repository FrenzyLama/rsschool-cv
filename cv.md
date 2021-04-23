# rsschool-cv

**Gleb Ilchyshyn**

### Contact details:
 **Email:** gleb.ilchyshyn@gmail.com
 **Discord:** Garred#4445

### Skills:
* Git
* Swift
* OOP

### Code examples: 
 
 ```
 func loginButton(_ sender: UIButton) {
        if let email = emailTextField.text, let password = passwordTextField.text {
            activityIndicator.startAnimating()
            DispatchQueue.global(qos: DispatchQoS.userInitiated.qosClass).async {
                self.request.loginRequest(email: email, password: password)
                NotificationCenter.default.addObserver(self, selector: #selector(self.logedIn), name: NSNotification.Name(rawValue: responseLogin), object: nil)
                NotificationCenter.default.addObserver(self, selector: #selector(self.incorrectParameters), name: NSNotification.Name(rawValue: errorLogin), object: nil)
            }
        }
    }
    
 ```
### Summary:
My goal is to become a iOS developer 

### Education:
Taras Shevchenko National University of Kiev 
### Language:
* English A2

