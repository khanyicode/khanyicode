
def create_3d_box(text):
    box_top = "+-" + "-" * len(text) + "-+"
    box_middle = f"| {text} |"
    box_bottom = "+-" + "-" * len(text) + "-+"
    
    return f"{box_top}\n{box_middle}\n{box_bottom}"

# Your README content
readme_content = """
👋 Hi, I’m @khanyicode
👀 I’m interested in software engineering and web development
🌱 I’m currently learning java but proficient in python, javascript, HTML ,Bootstrap, APIs, and Css
💞️ I’m looking to collaborate on python projects and web development projects as well as participate in hackathons
📫 How to reach me khanyisilemesha@gmail.com
"""

# Create 3D box around the content
boxed_content = create_3d_box(readme_content)

# Print or save the result
print(boxed_content)
