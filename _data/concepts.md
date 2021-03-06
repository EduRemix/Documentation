design_space: "The design space is the visual environment that features all the information available to the system and the user, and that enables users to exert control over the whole system. You may think of the design space as your desktop."

workspace: "The workspace is the entity storing all user-generated information, as well as the data structures embodied in the following hierarchies: crypto ecosystem, charting space and network."

node: "A node is a small data structure containing information which may be related to market information, trading intelligence, the operation of the system or other concepts. They are visually represented by icons on the workspace."

structure_of_nodes: "Nodes may be chained together forming structures of nodes. In every structure of nodes there is a parent node with offsprings. That is, a structure of nodes is a data structure composed of any node and its offspring."

parent-offspring_relationships: "Nodes in structures of nodes are chained to each other by so-called parent-offspring relationships. These relationships are visually represented by orange dotted lines, which may turn yellow or blue depending on certain visualization properties that the user may control. When nodes are chained together they form structures of nodes."

chain: "Nodes in the workspace may be unchained or detached from its parent, carrying all offspring with it. When a node is left unchained, it is no longer taken into account in the logic of the hierarchy, as it no longer belongs to it. When a node is chained back or reattached to the hierarchy, it goes back to being functional."

hierarchy: "A hierarchy is the representation of an overarching, top-level concept resulting in a long chain of nodes, usually with many ramifications. The system manages different types of hierarchies, each of them with a specific focus."

reference: "A reference is a mechanism by which information in a node is related to, or accessed by, other nodes. The ability of a node to establish a reference with another node enables the first to access the information or features entailed in the second one."

session: "A session refers to a backtesting, paper trading, forward testing or live trading session. When the term is used without specifying the type of session, then it refers to the overall concept by which a trading bot instance&mdash;based on datasets exposed as products by other bots&mdash;applies the trading logic defined on a trading system in any of the aforementioned modes."

sensor_bot: "A sensor bot is an algorithm that extracts raw data from external sources (i.e.: exchanges, Twitter, etc.) and stores it in a dataset that other bots may consume."

indicator_bot: "An indicator bot is an algorithm that processes information that other bots have generated, and produces elaborate datasets for others to consume."

bot: "A bot is an algorithm defined in a data mine. Superalgos manages three types of bots: sensors, indicators, and the trading bot."

trading_bot: "Based on datasets exposed as products by other bots (counting sensors, indicators and even other trading bots), a trading bot applies the trading logic defined on a trading system to, on one side, generate a complete trading simulation (outputting datasets that include trades, the action of strategies, validation of conditions, etc.), and on the other side, manage the execution of orders when on a forward testing or live trading session."

superalgos_protocol: "In conceptual terms, the Superalgos Protocol determines the structure in which the information describing a trading system is stored and guides how traders shall create and automate strategies. In practical terms, the protocol results in a file with a specific format capable of holding all the information concerning any number and variety of strategies. In its current early version, the protocol is the description of a JSON object which defines the desired automation."

hierarchies_directory: "The hierarchies directory is the part of the documentation that features a description of the complete catalog of nodes of each hierachy"

data_product: "A data product is a collection of datasets that bots output for others to consume."

dataset: "A dataset is a collection of plain-text files storing information in the form of arrays of records in the standard JSON format, although not as objects with named properties, but as arrays."

process: "A process is an algorithm defined in the process definition structure of nodes of the corresponding bot and data mine."

masters_data_mine: "Masters is a data mine shipping with the system. It features the main sensor bot, along with indicators offering the following data products: Candles, Volumes, Candle Stairs Patterns, Volume Stairs Patterns, Bollinger Bands, Percentage Bandwidth, Bollinger Channels, and Bollinger Sub-Channels."

sparta_data_mine: "Sparta is a data mine shipping with the system. It features indicators offering the following data products: Relative Strength Index (RSI 14), Simple Moving Average (SMA), Exponential Moving Average (EMA), and Moving Average Convergence/Divergence (MACD)."

pending: "balanceAssetA, balanceAssetB, overfitting, supported assets, supported exchanges, supported markets"

