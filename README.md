React - Stock Market Portfolio Tracker

Develop a Stock Market Portfolio Tracker as a single-page React application. This app will

allow users to view their stock holdings, track real-time prices, and simulate buying/selling

stocks.

Features:

1. Portfolio Summary Component

○ Display the total portfolio value, total number of stocks owned, and the user's

cash balance.

○ Use props to pass data into this component.

2. Stock List Component

○ Render a list of stocks available for trading. Each stock should display:

■ Stock Symbol (e.g., AAPL, TSLA)

■ Company Name

■ Current Price (mocked or fetched via API)

○ Allow users to click a stock to view details or trade it.

3. Trade Stock Component

○ Create a form to simulate buying or selling a stock. Fields include:

■ Stock Symbol (pre-filled based on selection)

■ Quantity

■ Trade Type (Buy/Sell via a dropdown)

○ Validate the trade:

■ Buy: Ensure sufficient cash balance.

■ Sell: Ensure the user owns enough of the stock to sell.

○ Update the portfolio and cash balance upon a successful trade.

4. Portfolio Details Component

○ Display the user's current holdings with details:

■ Stock Symbol

■ Quantity Owned

■ Current Value (quantity × current price)

○ Dynamically update values based on mock price changes.

5. API Integration (Mock or Real)○ Use useEffect to fetch stock data from a mock API or a free public stock API

(e.g., Alpha Vantage, Finnhub).

○ Simulate real-time price updates by refreshing prices every 10 seconds.

6. Dynamic Updates

○ Portfolio value and individual stock values should update dynamically as

prices change or trades are made.

7. Event Handling

○ Handle form submission for trades and button clicks for selecting stocks.

Example Structure:

plaintext

Copy code

1. Stock Market Portfolio Tracker

2. ---------------------------------

3. | Portfolio Summary | Portfolio Details |

4. ---------------------------------

5. | Stock List | Trade Stock |

6. ---------------------------------

Deliverables:

1. A single-page React application with multiple components.

2. Properly managed state using useState for data like portfolio, cash balance, and

stock prices.

3. Lifecycle management with useEffect for fetching/updating stock prices.

4. Clean and responsive design with basic styling or with ReGuidelines:

1. Functional Components:

Use functional components for a modular, reusable design.

2. State Management:

○ Use useState for managing state such as portfolio data, stock list, and cash

balance.

○ Use props to pass data between components.

3. Real-time Updates:

Simulate real-time stock price updates using setInterval within useEffect.

4. Validation:

Ensure trade validation logic prevents invalid trades.

5. After completing the code, commit the code and create a Pull Request out of it for

review.

6. Make sure you follow some methodology for problem solving and attach the sheet

you used
