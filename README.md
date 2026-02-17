# CoW Protocol Visualizer

Real-time visualizations for CoW Protocol order book and token network.

## Live Demos

- **[3D Order Drops](https://koeppelmann.github.io/cow_viz/index.html)** - Watch orders drop, settle into batches, and expire in a 3D visualization
- **[2D Token Network](https://koeppelmann.github.io/cow_viz/cowswap-network.html)** - Interactive network graph showing token relationships and order flow

## Features

### 3D Order Drops (`index.html`)
- Real-time order visualization with bouncing 3D spheres
- Order size reflected in ball size (logarithmic USD value)
- Color coding by order type (Market/Limit/TWAP), age, owner, or trading pair
- Batch settlement layers showing historical batches
- Audio feedback for new orders and settlements

### 2D Token Network (`cowswap-network.html`)
- Token nodes grouped by category (Stablecoins, ETH derivatives, Other)
- Edge thickness shows order volume between tokens
- Draggable tokens and category poles
- Click edges to see order list and depth chart
- Toggle between poles layout and circle layout

## Supported Networks

Ethereum, Gnosis, Arbitrum, Base, BNB Chain, Polygon, Avalanche, Linea, Lens, Sepolia (Testnet)

## Data Source

All data is fetched live from the [CoW Protocol API](https://api.cow.fi/).

## License

MIT
