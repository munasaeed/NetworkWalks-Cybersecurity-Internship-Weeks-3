Week 3 – Password Security and Recovery

Overview

This week focused on password security, password hashing, and password recovery techniques through practical cybersecurity exercises.

Practical Activities

1. Hash Calculator Exercise

Used the instructor-provided NetworkWalks hash calculator to explore password hashing and understand how hashes represent data.

2. Online Password-Cracking Exercise

Practised password recovery using the online learning resources provided by the instructor.

3. Password Recovery Using John the Ripper and Johnny

Worked with John the Ripper and its graphical interface, Johnny, to recover the password of an instructor-provided protected PDF.

Tools used:

* Kali Linux (WSL)
* Perl
* pdf2john.pl
* John the Ripper
* Johnny

Process:

1. Located the instructor-provided protected PDF.
2. Used pdf2john.pl to extract its password hash.
3. Saved the extracted hash in a text file.
4. Loaded the hash into Johnny.
5. Successfully recovered the password.
6. Verified the result by opening the protected PDF.

Key Learning Outcomes

* Understood the difference between passwords and password hashes.
* Learned how password hashes can be extracted from protected files.
* Explored different password recovery approaches.
* Gained practical experience with John the Ripper and Johnny.
* Understood the importance of responsible and authorized password testing.

Evidence

Screenshots of the practical exercises are included in this repository.

Security note: Raw hashes, recovered passwords, and instructor-provided protected files have been excluded to protect sensitive information.

Conclusion

Week 3 provided practical exposure to password security and recovery techniques, strengthening my understanding of tools and methods used in cybersecurity.