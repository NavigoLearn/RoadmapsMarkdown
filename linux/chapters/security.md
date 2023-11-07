# 13. Security

## 13.A Basic Linux Security Concepts

- We have already discussed some important concepts like permissions, ownership,
  SELinux and more. Further expanding on those, the basic security concepts in
  Linux also include Secure Shell configuration (SSH) also plays a vital role
  by providing a secure channel for remote login and command execution.
  Moreover, user authentication, which involves confirming the identity of a
  user attempting to access the system, is another crucial aspect in ensuring
  the Linux system is safe from unauthorized access. Understanding and properly
  implementing these security measures are key to maintaining a robust and
  secure Linux environment.
- On the topic of authentication. In an environment where security is of utmost
  importance such as in a server, you may restrict login to RSA keys only.
- [Video - How To Protect Your Linux Server From Hackers!](https://www.youtube.com/watch?v=fKuqYQdqRIs)
- [Article - Web Service Security](https://cheatsheetseries.owasp.org/cheatsheets/Web_Service_Security_Cheat_Sheet.html)

## 13.B AppArmor

- AppArmor, which stands for Application Armor, is a Linux Security Module 
  (LSM). It's a mandatory access control framework that restricts programs'
  capabilities with per-program profiles. These profiles can enforce a variety
  of access controls, including limiting the network access of a program,
  restricting the files a program can read, write, or execute, and more. In
  short, AppArmor allows system administrators to restrict system-wide
  applications by applying specific security policies to them. This increases
  the overall security of the system by reducing the potential attack surface of
  an application.
- [Video - What is AppArmor | AppArmor commands](https://www.youtube.com/watch?v=KYM-Dzivnjs)
- [Article - AppArmor](https://wiki.archlinux.org/title/AppArmor)
