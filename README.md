# Function to display academic background
def show_academic_background():
    print("📚 Academic Background")
    print("=" * 50)

    education = [
        {
            "Degree": "National Diploma in Computer Engineering",
            "Institution": "Osun State Polytechnic, Iree, Nigeria",
            "Year": "2012 – 2015"
        },
        {
            "Degree": "BSc in Mathematics",
            "Institution": "Osun State University, Osogbo, Nigeria",
            "Year": "2015 – 2019"
        },
        {
            "Degree": "MSc in Mathematics (Specialization: Mathematical Modelling)",
            "Institution": "Osun State University, Osogbo, Nigeria",
            "Year": "2020 – 2022"
        },
        {
            "Degree": "MSc in Cybersecurity Technology",
            "Institution": "Northumbria University, London Campus, UK",
            "Year": "2024 – Present"
        }
    ]

    for edu in education:
        print(f"\n🎓 {edu['Degree']}")
        print(f"🏫 Institution: {edu['Institution']}")
        print(f"📅 Year: {edu['Year']}")
    print("=" * 50)

# Call the function to show academic background
show_academic_background()
![python code for academics bacground](https://github.com/user-attachments/assets/6a2241ca-f6c0-40ce-809e-aeb581c96fa0)
