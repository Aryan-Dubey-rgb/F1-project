# Formula 1 Race Intelligence

Formula 1 Race Intelligence is a data visualization project created with Tableau to explore and analyze various aspects of Formula 1 racing. The project transforms raw racing data into meaningful visual insights, making it easier to understand historical performance, compare statistics, and identify trends across different seasons. It covers several important areas, including constructor and driver performance, tyre-compound analysis, Grand Prix hosting statistics, podium records, and race reliability.

## Project Scenarios

### 1. F1 Team Performance Strategist

This scenario focuses on understanding the competitive performance of Formula 1 teams and drivers through championship statistics and race-related data.

- **Constructor Championship Points Trend:** visualizes the changes in championship points earned by different teams over successive seasons, helping compare their performance over time.
- **Tyre Compound Performance by Circuit Type:** explores the relationship between starting tyre compounds, circuit categories, and podium results to identify performance patterns.
- **Driver Talent and Performance Ranking:** evaluates and ranks drivers based on their performance statistics during a selected season.

### 2. Motorsport Broadcast Analyst

This scenario presents historical Formula 1 statistics in a way that makes major achievements, records, and racing trends easier to understand and communicate.

- **All-Time Driver Points Leaderboard:** provides a ranking of drivers based on the cumulative championship points they have earned throughout the available seasons.
- **Countries Hosting the Most Grand Prix Rounds:** highlights the countries that have hosted the highest number of Grand Prix events by counting distinct races.
- **Podium Achievements by Driver and Team:** compares the podium accomplishments of individual drivers while showing their association with different teams.

### 3. F1 Technical Regulation Analyst

This scenario examines retirement statistics and race-completion performance to provide a better understanding of reliability-related trends in Formula 1.

- **DNF Reasons by Team:** displays the different recorded reasons for races not finished by drivers, allowing comparisons between teams.
- **DNF Patterns by Circuit Type and Driver:** analyzes retirement patterns across different drivers and circuit categories to identify variations in DNF frequency.
- **Driver and Team Reliability Trend:** tracks race-completion rates across multiple seasons to compare the reliability performance of drivers and teams.

## Dataset Description

The project is developed using multiple data tables, with each table providing a different category of information required for the analysis and visualization process.

| Sheet | Description |
|---|---|
| `circuits` | Contains information about Formula 1 circuits, including their relevant details and characteristics. |
| `championship_standings` | Provides driver championship standings and the points recorded for each season. |
| `lap_intelligence` | Contains lap-level data that supports detailed analysis of race performance. |
| `qualifying_results` | Stores information about qualifying sessions and their respective results. |
| `race_results` | Includes race outcomes, driver and team information, finishing positions, tyre details, and retirement records. |

## Sharing Through Tableau Public

The project can be published through Tableau Public so that other users can access and interact with the visualizations online without needing to open the original workbook.

1. Launch the workbook in Tableau Public Edition.
2. Log in using an existing Tableau Public account or register for a free account.
3. Navigate to **Server → Tableau Public → Save to Tableau Public**. The exact menu wording may differ depending on the software version.
4. Once the publishing process is complete, visit your Tableau Public profile to locate the uploaded project.
5. Click **Share** to copy the public link, which can then be distributed to other users.

## Tools Used

The development and presentation of this project involve the following tools and platforms:

- **Tableau** — used for creating interactive visualizations, charts, dashboards, filters, and story presentations.
- **Microsoft Excel / Spreadsheet Data** — used for inspecting, organizing, and preparing the data before visualization.
- **GitHub** — used to organize project files, maintain the repository, track modifications, and make project resources accessible.

## Notes and Limitations

- The findings are based entirely on the seasons and records provided in the available dataset. The most recent season may not contain complete information, so its statistics should be interpreted carefully.
- Championship standings are maintained at the individual driver level. As a result, calculating total points for a team requires accurate driver-to-team associations for the corresponding season.
- The country in which a Grand Prix takes place should not be interpreted as the nationality of its participating drivers. Driver nationality analysis requires a reliable nationality field or a separately verified reference table.
- DNF-related analysis depends on the status classifications and retirement information stored in the dataset. These classifications should be reviewed to ensure that the results are interpreted correctly.
- Combining tables with different levels of detail may introduce duplicate records and affect calculated totals. It is important to validate row counts and aggregated results after joining tables. Tableau relationships should be used where appropriate.
- The visualizations help reveal trends, comparisons, and relationships within the available Formula 1 data. However, these patterns alone cannot establish the actual causes behind specific race results, driver performance changes, or retirement events.
