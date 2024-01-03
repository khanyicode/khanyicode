def create_3d_text(text):
    lines = []
    lines.append(f"  {text}  ")
    lines.append(f" / {text} \\ ")
    lines.append(f"| {text} |")
    lines.append(f" \\ {text} / ")
    lines.append(f"  {text}  ")

    return "\n".join(lines)

# Your README content
readme_content = """
👋 Hi, I’m @khanyicode
👀 I’m interested in software engineering and web development
🌱 I’m currently learning java but proficient in python, javascript, HTML, Bootstrap, APIs, and Css
💞️ I’m looking to collaborate on python projects and web development projects as well as participate in hackathons
📫 How to reach me khanyisilemesha@gmail.com
"""

# Create 3D text around the content
boxed_content = create_3d_text(readme_content)

# Print or save the result
print(boxed_content)
