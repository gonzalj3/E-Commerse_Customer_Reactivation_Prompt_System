# Data Directory

This directory contains the foundational data used for the customer reactivation prompt engineering project.

## Company Context: Allbirds

**Allbirds** is a sustainable footwear company founded in 2016, known for creating "the world's most comfortable shoes" using innovative eco-friendly materials like eucalyptus tree fiber and merino wool. The company has built a strong brand around sustainability, comfort, and simplicity, targeting environmentally conscious consumers willing to pay premium prices ($78-$140) for ethically-made footwear.

### Brand Characteristics
- **Mission:** Make better things in a better way
- **Core Values:** Sustainability, comfort, simplicity, transparency
- **Product Philosophy:** Lead with benefits (comfort, sustainability impact) rather than discounts
- **Customer Base:** Eco-conscious professionals, active lifestyle enthusiasts, conscious parents, and minimalist consumers

## Data Files

### `customers.csv`
This file contains **100 realistic customer records** representing Allbirds' diverse customer base. The data was synthetically generated to reflect typical purchasing patterns for a sustainable footwear brand.

**Key Characteristics:**
- **Geographic Distribution:** Major US cities (San Francisco, Los Angeles, New York, etc.)
- **Age Range:** 18-80 years (concentrated in 25-55 demographic)
- **Purchase Categories:** Automotive, Electronics, Health, Home & Garden, Beauty, Books, Sports, Clothing
- **Spending Patterns:** $96-$25,260 total lifetime value
- **Purchase Frequency:** 1-50 transactions per customer
- **Engagement Scores:** 10.5-87.8 (indicating varying levels of brand engagement)

**Note:** While the CSV shows diverse product categories, in the context of this project, these represent different Allbirds product lines and customer engagement patterns rather than literal automotive or electronics purchases.

### `customer_personas.json`
Ten detailed customer personas derived from analyzing patterns in the `customers.csv` data. Each persona represents a distinct customer segment with specific:
- Demographic characteristics
- Pain points and motivations
- Communication preferences
- Spending behaviors
- Recommended reactivation strategies

### `sample_scenarios.json`
Ten realistic customer reactivation scenarios that an Allbirds marketing team might encounter, including:
- High-value customer churn
- Seasonal purchase dormancy
- Price-sensitive purchase pauses
- Lifestyle changes affecting purchase patterns

### `company_profile.json`
Comprehensive business profile for Allbirds including:
- Brand positioning and voice guidelines
- Product portfolio and pricing strategy
- Customer segmentation approach
- Sustainability messaging framework
- Reactivation strategy recommendations

## Project Context

These data files support a prompt engineering case study demonstrating how AI-powered customer reactivation can be optimized for a specific brand context. The Allbirds profile provides realistic constraints and opportunities:

### Why Allbirds Works Well for This Study:
1. **Clear Brand Voice:** Authentic, educational, sustainability-focused
2. **Premium Positioning:** Discounting isn't the primary reactivation tool
3. **Seasonal Patterns:** Natural reactivation opportunities (summer breezers, winter wool shoes)
4. **Replacement Cycles:** 12-18 month product lifespan creates predictable reactivation windows
5. **Values-Driven Customers:** Respond to sustainability impact and comfort benefits

### Customer Relationship Dynamics:
- **First Purchase:** Often Tree Runners ($98) as gateway product
- **Repeat Behavior:** Average 18-month cycle, different seasonal styles
- **Reactivation Triggers:** Season changes, shoe wear-out, lifestyle changes, sustainability milestones
- **Preferred Communication:** Educational content over sales pressure, sustainability impact updates, comfort-focused messaging

This data foundation enables testing of prompt engineering approaches that balance brand authenticity with conversion optimization, making it an ideal case study for advanced marketing AI applications.