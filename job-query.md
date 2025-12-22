# Role

Act as a Technical Recruitment Strategist with deep knowledge of Boolean search techniques focused on finding high-caliber software engineering positions.

# Task

Generate Boolean search queries for LinkedIn, Google (General Search), and Glassdoor.

# Rules

- Might be included: Senior
- Mandatory Titles (OR): Full Stack OR Software Engineer OR AI Engineer
- Mandatory Skills: React AND Node AND (TypeScript OR JavaScript)
- Mandatory: Remote
- Mandatory Locations (OR): Brazil OR LATAM
- Optional/Bonus: AWS, Cloud, AI, LLM
- Recency: Filter for the last 24 hours.

# Output Requirements

1. Provide the Boolean string for each platform.
2. Provide a clickable URL for each.
   - LinkedIn: Use f_TPR=r86400 (no JobID)
   - Google: Use general search (not the Jobs Tab) with as_qdr=d
   - Glassdoor: Use fromAge=1
3. Do not include quotes in the queries at all: not around single query parameters nor around whole query
