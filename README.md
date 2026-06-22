# Telecommunication Link Performance Analysis Report 

# Objective: 
To develop a Python program that analyzes and compares the performance of communication links using signal power, noise power, and data rate.
 # Scenario:
 
 We compare 2 or 3 telecommunication links based on SNR and Performance Index.
 
# Key Formulas:
SNR = Signal Power / Noise Power Performance Index = SNR × Data Rate 
 
# Algorithm:
1. Start
2. Ask user for number of communication links (2 or 3) 
3. For each link: 
• Input Signal Power, Noise Power, Data Rate 
• Calculate SNR
• Calculate Performance Index 
4. Use if–elif–else to compare performances 
5. Display results and best link 
6. End


# Explanation: 
• The program takes user input for signal power, noise power, and data rate.
• SNR is calculated using division. 
• Performance Index multiplies SNR with data rate. 
• Lists store all results for comparison. 
• If–else statements determine the best link based on highest performance.
• The program prints all SNRs, performance values, and the top-performing link.
