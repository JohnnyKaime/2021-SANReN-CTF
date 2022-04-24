https://www.sanren.ac.za/sanren-cyber-security-challenge-2019-winners/


# SANReN CTF competition in 2021:
  ## Intro:
  We are HappyTreeFriends :D  
  We Who Shall Not Be Named - The anti pigeons squad

## Network Data:
  ### Wireshark Fun:
    ```
    Given a PCAP file we used Wireshark to view it, we first tried filtering by http request type post, but got nothing, there we searched for string type "flag" and found the flag.
    ```

  ### Wireshark Fun Part2:
    ```
    Given a PCAP file we used Wireshark to view it, this challenge was different from the previous as the description said encoding http header stream, our team did a http post filter and got nothing valuable, when we tried using get request we found messages with base64 encryption, after decrypting all 10 or so messages and reading the "hint" contained in the decrypted messages, we found the flag, but the last digit "7" must be removed.
    ```

  ### What Type Of Attack
    ```
    Given a "0adc27b619b40af933fabd4908004500002836e300002506fc4bac1e0042341e8223b3348011bd4b0250000000005029040056380000" what is the raw attack, flag format in 0xXXX. 
    Using hex reader and search we obtained 0x029 
    ```

  ### What Type Of Attack Part 2
    ```
    What type of attack does this represent. (One Word)
    xmas
    ```
  
## Steganography

  ### Hidden Image
    ```
    Give ProblemChessB4-1000x1000Merged.png
    ```
