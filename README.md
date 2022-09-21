# MeerkatAnalizer
![logo](logo.png)  
### _Let us watch over the security of your project_ 
Meerkat is powerfull AI based system to security and trust assessment of the commits and pull requests to your repository.  
Our main goal is detecting malicious changes in your project that could be (or cause) a backdoors.  
<br>
## Why should you use Meerkat?  
The main reasons for usage of the MeerkatAnalizer are:  
1. **Safer project**  
You don't need to worry about corrupted or angry employee that could destroy reputation of your solution.  
2. **Faster software developing**  
Your project menagers and security team will spend less time for changes analysis.  
3. **Modern technologies**  
Usage of the modern and well known technologies like huggingface and tensorflow.  
4. **Work out of the box**  
You do not to write code or complex configuration just connect our solution to your CI/CD  
<br>  
  
## How does it works?  
MeerkatAnalizer should be run as part of the CI/CD.  
When new pull request or commit shows up our solution will check changes in three layers:  
1. Vulnerability research - you can use our engine or configure usage of the snyk  
2. AI based backdoor detection - our AI is looking for unusual and suspicous code that could cause:  
    * Remote Code Execution  
    * Data breach  
    * Ransomware attack  
    * Steal credentials  
3. Application fuzzing - fuzz binary / endpoints with AFL and our AI that looks for suspicious behavior (executing unpredicted command or sending packets). 
