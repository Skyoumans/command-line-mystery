1. cd command-line-mystery
    # changed to command line mystery directory

2. grep "CLUE" mystery/crimescene
    # filtered out the related clues to the crime

3. grep Annabel mystery/crimescene
    # found all addresses where "Annabel"s lived at

4. head -n 40 mystery/streets/Hart_Place | tail -n 1

5. cat mystery/interviews/interview-47246024
    # not our witness

6. head -n 176 mystery/streets/Haley_Street | tail -n 1

7. cat mystery/interviews/interview-871877
    # not our witness

8. head -n 179 mystery/streets/Buckingham_Place | tail -n 1

9. cat mystery/interviews/interview-699607
    # Ms Church saw a car leaving the scene, Blue Honda, License plate starting with "L337" and ending with "9"

10. grep -A 5 "L337" mystery/vehicles
    # pulled up all vehicles matching description of license plate and checked to see who matched the description provided by the barista and Ms. Church

11. cd mystery/memberships
    # changed into memberships database

12. cat AAA Delta_SkyMiles Terminal_City_Library Museum_of_Bash_History | grep "Joe Germuska"
    # checked memberships of Joe Germuska vs the contents of the wallet. He came back positive for two of the four found.

13. cat AAA Delta_SkyMiles Terminal_City_Library Museum_of_Bash_History | grep -c  "Jeremy Bowers"
    # checked the number of memberships that matched the content of the wallet. Came back a 100% match

14. Jeremy Bowers is the shooter!!!