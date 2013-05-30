### Posh-Remoting - Incompleteware

  This presently doesn't work, but I need to move this code off of my
  local machine and into a GitHub repo.

* Use friendly names to connection to WinRM sessions,
  rather than connecting by hostname or ip?
* Store remote WinRM session credentials in your local account
  securely. HINT: stashing passwords in your profile is *not* secure
* Automatically establish connections in the background, so that they
  are ready and waiting for you to connect to.
* Heal these connections after hibernating and resuming your machine?

That's the basic premise.  This is very early work and will require
quite a bit of polishing to move forward, but the initial concepts are
sound.

* The Session is locked down with a single master password.
* This password controls access to individually encrypted files, which
  contain the real credentials.



