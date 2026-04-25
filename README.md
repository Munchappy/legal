from weasyprint import HTML

# Content for the Markdown file
markdown_content = """# Munchappy Legal Hub

Munchappy is a local commerce and food delivery infrastructure operated by **The Candeed Corp**. We exist to restore fairness, transparency, and simplicity to the digital marketplace. Our platform is built on the belief that local commerce only thrives when it serves the human beings who power it: the customers, the restaurants, and the couriers.

## Mission: Reclaiming Local Commerce
Our mission is to make food delivery fair again. We are building more than a logistics tool; we are creating a system designed for people. We believe that technology should be a bridge, not a barrier. 

* **Customers** deserve the honesty of the actual menu price. 
* **Restaurants** deserve to keep the fruits of their labor to sustain their craft. 
* **Couriers** deserve a stable and transparent partnership that respects their time and effort. 

Peastash brings all three together on a platform where the architecture is governed by logic and the experience is guided by human values.

## Vision: A System Built for Humans
We aim to become the most trusted and transparent local commerce system—a place where the community wins together. Our vision is to eliminate the exploitation often hidden within "black box" delivery algorithms. We are building for a future where local commerce is simple, fast, and fundamentally fair. No hidden layers, no inflated costs—just a direct connection between the kitchen and the home.

## About the Platform
Peastash connects customers with local merchants and independent couriers through a high-performance native infrastructure. Our model is built on the principle of radical transparency:

* **For Customers:** We provide access to local favorites without the burden of hidden markups. You see the real price, and you receive the real food.
* **For Restaurants:** We provide the infrastructure to digitize your business without sacrificing your margins. We view ourselves as a partner in your growth, not a tax on your existence.
* **For Couriers:** We offer a platform built for independence and reliability. We facilitate the connection between you and the community you serve, ensuring your contributions are valued and your earnings are clear.

These legal documents outline the terms, policies, and agreements governing the use of the Peastash ecosystem.

---

## Legal Documents

- **[Terms of Service](TERMS_OF_SERVICE.md)**
  *The governing rules for our shared digital space.*
- **[Privacy Policy](PRIVACY_POLICY.md)**
  *Our commitment to protecting the data of the individuals we serve.*
- **[Courier Agreement](COURIER_AGREEMENT.md)**
  *The foundation of our partnership with independent delivery professionals.*
- **[Merchant Agreement](MERCHANT_AGREEMENT.md)**
  *The terms governing our support of local culinary partners.*

---

## Contact Information

**The Candeed Corp (DBA Peastash)** 251 Boulevard  
Hasbrouck Heights, NJ 07604  
Email: **support@peastash.com**

*Last Updated: April 25, 2026*
"""

# Save as a .md file
with open("munchappy_legal_hub.md", "w") as f:
    f.write(markdown_content)

print("munchappy_legal_hub.md")
