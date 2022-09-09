## Recreation Steps:

1. Install python webserver:
   `git clone https://github.com/Gameknight-Bit/StudentCouncilWebpage.git`

Or from this link: https://github.com/Gameknight-Bit/StudentCouncilWebpage

2. Install flask on python 3.9.x `pip install flask`
3. Make sure to run the webserver on ASDPublic (doesn't have access to ASDPrivate)
4. Run main.py `python3 path/to/file/main.py`
5. Go to or link in python output terminal on ASDPublic on a different device (should not show up) and ASDPrivate on a different device (should show up)
6. **Voila**, For some reason the webserver is able to access ASDPrivate without being blocked and without a password.

## Reasons why it matters:
I'm not exactly sure how the network for West Shamokin is set up; however, having the ability to host a website locally from 2 separate wifi networks may allow for other "vulnerabilities" in the network.
It also allows for access to the ASDPrivate network without a password (which could be bad if a student or malicious exploiter got a hold of it)

I am not exactly sure how local wifi websites are hosted work exactly with Flask; however, I do know that being able to access ASDPrivate from ASDPublic is probably a bad thing

