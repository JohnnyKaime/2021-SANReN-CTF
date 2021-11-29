<h1>SANReN CTF competition in 2021:</h1>

<h2>Network Data:</h2>
  <h3>Wireshark Fun:</h3>
  <p>
  Given a PCAP file we used Wireshark to view it, we first tried filtering by http request type post, but got nothing, there we searched for string type "flag" and found the flag.
  </p>
  <h3>Wireshark Fun Part2:</h3>
  <p>
  Given a PCAP file we used Wireshark to view it, this challenge was different from the previous as the description said encoding http header stream, our team did a http post filter and got nothing valuable, when we tried using get request we found messages with base64 encryption, after decrypting all 10 or so messages and reading the "hint" contained in the decrypted messages, we found the flag, but the last digit "7" must be removed.
  </p>
