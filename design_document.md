# Problem Statement

## DOMAIN: Communal living. 

Formally, communal living may be defined as the state of living in some building, in which some spaces and resources are shared/communal and others are not, and residents share collective responsibility for these resources and spaces. For example, 5 people living in the same house is communal living, while 5 people living in the same apartment building in individual apartments is not. Even if the apartment building has some shared ammenities, it is not communal living unless the residents collaborate to maintain those ammenities (rather than a landlord).

Communal living need not be among a single 'family'. Residents will generally have separate finances, implicit expectations of privacy and personal property, and so forth. This is in contrast to the implicit expectation that a family unit's assets are owned and shared by all members of the family by default unless negotiated otherwise. In fact, communal living may even take the form of multiple families sharing a household.

In a communal living scenario, the primary stakeholders are the residents. They must maintain upkeep of the residence and its communal resources, such as by cleaning rooms, taking out the trash, interfacing with a landlord, and so forth. To make each others' lives easier, they may choose to pool their time and resources to designate items as 'communal', i.e. intended to benefit any members of the household for use by all residents who wish to use the item(s). For example, one resident might designate their tupperware as communal, another might designate their pots and pans as communal, and another still might purchase disposable items such as paper towels and toilet paper and designate them as communal. This reduces the collective amount of labor the residents have to do in total: forcing every resident to buy their own toilet paper and paper towels requires much more individual labor and is much more logistically complicated. However, communal resources pose logistical challenges in and of themselves.

## BAD SITUATIONS

### Confusion over item status
It can be difficult for residents to keep track of which items are communal and which are not. As the number of residents grows, the amonut of communication required for uniform understanding grows quadratically. An individual resident may suffer from not realizing that they could be taking advantage of a communal item they don't know is communal, and they may also suffer from another resident or residents erroneously believing some item or items belonging to them are communal when they are not (such that the item is used without permission). 

For example, Alice buys expensive moisturizing tissues that are less irritating on skin when used, and intends for them to be communal. Bob gets sick, but isn't aware that he can use these tissues, so he just uses the cheap packs of pocket tissues he has in his room, causing skin irritation beneath his nose over the course of his illness as he uses the tissues.

For another example, Alice buys paper plates and stores them near the dinnerware, intending to use them on lazy days where she doesn't want to wash a dish after eating. Bob, erroneously assuming them to be communal like the rest of the dinnerware, uses the paper plates regularly unbeknownst to Alice, until no plates remain when she looks to use one, much to her chagrin.

### Immaterial responsibility
The relationships surrounding the establishment of items as communal are not formally defined. If a particular resident goes out of their way to regularly buy consumable communal items, such as food ingredients, they may feel unduly burdened by the rest of the household and grow resentful. If a particular resident does not contribute communal items but still regularly uses communal items, they may be perceived as a freeloader taking advantage of the generosity of the other residents in the houeshold.

For example, Carol keeps the kitchen stocked with a wide variety of spices and condiments for cooking. She designates them as communal, allowing others in the household to use them, but over time the cost of maintaining the inventory becomes a financial burden, and she laments the lack of recognition of this from her roommates. David, meanwhile, starts to feel like he's not spending enough on communal items for the household in comparison to Carol, and starts haphazardly buying products and making them communal to avoid feeling like a burden or freeloader, even though those products might not be particularly useful to the household. Eventually, Carol simply stops restocking the kitchen, to the detriment of all residents, and nobody takes her place.

### Accounting fatigue
To avoid the responsibility problem, households often intuitively try to split the costs of communal items equally. This requires significant manual labor in the form of bookkeeping, and can lead to fatigue and interpersonal strain when some household members care more than others: those who care more may feel that the others are insensitive to their financial stress, while those who care less may feel that they're getting nickel-and-dimed by the others.

It is also challenging to keep inventory of communal items, particularly consumable communal items. If an item runs out and needs to be replaced, someone has to take point on tracking the stock of the item and replacing it when it runs out. 

## WORKAROUNDS AND COMPARABLES
Generally, most households simply allow norms to establish themselves over time without explicit negotiation, unless the established norms cause an experience negative enough for a particular resident to speak out. Individual residents see the economic benefits of permanent communal items (cookware, furniture, etc) and material benefits of temporary communal items (toiletries to improve household hygiene, etc), and naturally approach them with minimal explicit planning or negotiation. Eventually, some conflict around communal items may arise (accidental use of a non-communal item, some residents taking on significantly more responsibility for managing and acquiring communal items than others, economic pain from costs of communal items not being distributed amongst residents, fatigue from tracking the status of items and reimbursements, etc), which in the worst case may lead to rifts in the household and decreased cooperation and trust. The 'workaround' is to simply hope that nothing bad happens and the positive status quo from the emergent norms is productive and maintained. 

Some apps, such as Splitwise, can alleviate some of the bad situations, such as by making bookkeeping and reimbursement easier. Splitwise in particular has the following shortcomings:
- The app is focused around one-time costs
- The app is designed around individual users having complex economic relationships with other users in a graph that may not necessarily be dense
- The app is not designed for household use or communal living, so it does not address the following bad situations:
  - Confusion over item status: in Splitwise, every interaction is reduced to a single purchase/expense, without addressing the purpose of those purchases in a directed way. A communal item that was not a recent purchase may be forgotten. If a consumable communal item is consumed, there is no mechanism to document its absence. 
  - Inventory fatigue: there is no way to designate responsibility for a purchase until after the purchase is made. Keeping items stocked remains a chore of volition, and can easily be forgotten. The app does not address the challenge of keeping inventory of items at all, only purchases.
  - Immaterial responsibility: the cost of a purchase must be divided between individuals the moment that purchase is registered. There is no simple mechanism for allowing people to later decide to take on a greater or lesser portion of the purchase, because all accounting is immediate. Responsibility must be determined in order for the purchase to be documented and marked for reimbursement, requiring synchronous communication for what should be an asynchronous chore or unsatisfying compromises in cost splitting that bypass the need for immediate communication.

## CORROBORATION
Evidence for these bad situations is mostly anecdotal, based on firsthand testimony and personal experience. However, some social media posts discuss relevant issues: 
- https://www.reddit.com/r/badroommates/comments/1ae0peu/roommate_wants_to_nickel_and_dime_on_shared/
- https://www.facebook.com/groups/684980879834434/posts/1170636721268845/
- https://www.psychologytoday.com/us/blog/social-instincts/202504/2-signs-youre-the-cinderella-roommate

## SOLUTION SKETCH
### CONCEPT: Stakepaying
Under mutual agreement, all *n* residents agree that whenever a communal item is purchased or otherwise applied to the household, they implicitly may be responsible for up to 1/*n*th of the price. Any resident may, for any reason, decide to take responsibility for a greater share of the price: perhaps they feel they will get more benefit out of the communal item than others, or they want to take on more burden out of kindness, empathy, guilt, or any other reason. Any resident may also disown any communal item when this responsibility is being allocated, distributing their burden amongst remaining residents and forfeiting their right to use the item as communal at any point in the future. Items may also be marked as needing a refill, to ease inventory management.

Example: Alice, Bob, Carol, and David cohabit a residence. The concept is applied as follows:

Alice buys a vacuum cleaner and designates it as communal. All residents pay 25% of the cost, and all residents use the item.

Bob buys a bottle of Frank's RedHot sauce and designates it as communal. Carol does not eat spicy food, so she disowns the hot sauce. Alice, Bob, and David each pay 33% of the cost, and only they use the item.

Alice sees the hot sauce is almost gone, so she marks it as needing a refill. David sees this, and buys a bottle while out shopping. The arrangement for the old bottle of hot sauce is reused for the refill, so Alice, Bob, and David each pay 33% of the cost, and only they use the item.

Carol buys an air fryer and designates it as communal. However, she wants to own it for herself and have the ability to take it with her on trips, so she decides to take on the entirety of the cost herself after negotiating the terms of use with the other residents. Carol pays 100% of the cost, and all residents use the item, except when Carol takes it away from the house while she travels.

David feels guilty for not contributing as much to the household as he feels he should. He sees Alice has recently purchased soap, toilet paper, and paper towels to replenish the bathrooms. He decides to pay 40% of the cost of the items, to assuage his guilt and show his appreciation of his housemates. David pays 40% of the cost, and Alice, Bob, and Carol each pay 20% of the cost, and all residents use the items. 

The benefits of such a system are clear. As an added bonus, any tool used to track the paid stakes of communal items necessarily resolves confusion over what items are communal to the household: anything tracked is necessarily communal and can be used without fear, and anything not tracked may not be communal and use must be negotiated with the owner of the item.

Note that this only change of behavior *required* by this system is that of the residents acquiring items. When acquiring communal items, they must register those with whatever tool manages this system. If all other residents take no action, they are implicitly responsible for 1/*n*th of the items' cost, and will have those costs levied on them alongside the costs normally levied on them as members of the household (i.e. rent). Acquiring duplicate items (such as refilling a consumable communal item) can further decrease friction by automatically using the allocations used for the last item. 

Friction may be decreased through mechanisms to make data entry easier. For example, an application implementing this concept could take advantage of the following:
- Prices could be read via OCR from photos
- Product information could be obtained through barcode scanning (UPC lookup), also read by photo
- Fields other than name and price can be autofilled or left blank without compromising the functionality of the concept
- Fields with values common among multiple items could be selected via dropdown/autofill (eg 'location in house' could automatically choose between 'kitchen', 'bathroom', etc)


# Application Pitch 

## Communal Item Tracker

Communal Item Tracker makes it less hard for groups of several housemates to keep track of communal items.

### Key Features

1. Item Tracking
Communal Item Tracker is a single source of truth for your household's communal items. Track what's communal, where it's stored in the house, what it looks like, who owns it (if applicable), and how much it cost.

2. Cost splitting
Bookkeeping without the guilt. Track how much everyone owes or is owed while splitting the cost of communal items you buy. Split everything equally by default, claim more or less of whatever you want whenever you want. Claim 100% of the crock pot you want to take with you when you move out, and 40% of the eggs if you eat more of them than everyone else, and 0% of the milk if you're lactose intolerant. 

3. Information Autofill
Scan barcodes to autofill information about what you're buying, making it nearly effortless to track what you buy.


# Concept Design

```
**concept** ItemTracking
**purpose** track the status of communal items
**principle** users register items as communal, and note information about them
**state** 
a set of Items with
	a String name 
	a Number price 
	a Number uuid
	a set of Attributes attributes
a set of Attributes with
	a String key
	a String value
**actions**
	registerItem(name: String, price: Number, attributes: Set<Attributes>) : return (item: Item)
		**then**
			create a new Item item with the following properties:
				name name
				price price
				some uuid not used by any other Item in Items
				attributes attributes
			return item as item
	updateItem(item: Item, name?: String, attributes?: Set<Attributes>) : return (item: Item)
		**where** name is set
		**then** set item.name to name
		**where** attributes is set
		**then** set item.attributes to attributes
		return the Item as item
	updateItemAttribute(item: Item, attribute: Attribute) : return (item: Item)
		**then**
			set item.attributes[attribute] to attribute
			return item as item
	getItem(uuid: Number) : return (item: Item)
		**where** an Item with uuid uuid exists
		**then** return that Item as item
	listAllitems() : return (items: Set<Items>)
		**then** return the set of Items as items
	deleteItem(item: Item)
		**then** delete the item
		
```
A note on Attributes: they're not restricted because the concepts don't require them to be, but some features that might make use of attributes could include:
- a "needs refill" attribute, that when set to true indicates to the users that the item is almost or fully consumed and a new one needs to be bought
- a "location" attribute, indicating where in the house the item is stored
- a "picture" attribute, storing a picture of the item (perhaps as a URL or as base64)
- various attributes storing product metadata that might be automatically retrieved from some UPC lookup, or some other source of metadata about the item


We take cryptographically secure Hashing for granted as a primitive concept that need not be defined

```
**concept** UserData [Hashing]
**purpose** authenticate users and store information about them
**principle** users authenticate with a username and password, and perform actions that are logged
**state** 
a set of Users with
	a String user
	a Number outstandingBalance
	a Boolean deleted // users cannot actually be deleted, because stale references would cause too many problems
	a Hash password
a set of Logs with
	an Action action
	a Time time
	a User user
**actions**
	registerUser(name: String, password: String) : return (user: User)
		**where** no user in Users has user name
		**then** 
			create a new User with user name, outstandingBalance 0, and password Hashing.hash(password)
			return the User with user name as user
	authenticateUser(name: String, password: String) : return (user: User)
		**where** there exists a user in Users where user.name = name and user.password = Hashing.hash(password)
		**then** return that user as user
	deleteUser(user: User)
		**where** user.deleted is false
		**then** set user.deleted to true
	undeleteUser(user: User)
		**where** user.deleted is true
		**then** set user.deleted to false
	performAction(user: User, action: Action)
		**then**
			perform Action action
			create a Log with:
				action action
				time the current time (at which the action was performed)
				user user
	deleteLog(log: Log)
		**then** delete log from the set of Logs
	auditLogs(startTime: Time, endTime: Time) : return (logs: Set<Logs>)
		**then**
			create an empty set of Logs logsRet
			for each log in the global set of Logs:
				if log.time is between startTime and endTime, then make a copy of it and add that copy to logsRet
			return logsRet as logs
```
A note on Logs: one expected use case is checking whenever a Log notes an action involving users other than the user performing the action, in order to allow those users to be notified. For example, setStakeIndividual run by a user other than the one for whom a stake is being set. 

Actions are not restricted in terms of which user can perform which actions in and of themselves, because Users cannot fundamentally be in any sort of adversarial relationship with each other without deprecating the system: the presence of a bad actor in the household makes the use of communal items generally infeasible in the first place. The primary purpose of authentication is just to track *who* does what for accountability, and to make sure that random people (anyone who is not part of the household) cannot haphazardly affect the system.

```
**concept** StakePaying [ItemTracking, UserData] 
**purpose** track who is to pay how much for each item, how much money each user owes or is owed
**principle** users register items as communal, 
              and claim shares of their costs
**state** 
a set of Items with
	inheritance of all properties and methods as defined in ItemTracking
	a set of Shares shares 
	a User|None fronter 
a set of Shares with
	a User user
	a Number percentage
	a Boolean manual
**actions**
	registerItem(name: String, price: Number, attributes: Set<Attributes>, fronter?: User) : return (item: Item)
		**where** fronter exists in Users or price is 0
		**then** 
			create a new Item item with ItemTracking.registerItem(name, price, attributes)
			let n represent the number of existing Users for whom user.deleted is false
			set item.shares to a set of Shares shares containing n shares, where each share contains:
				an existing User user that none of the other Shares in shares use for whom user.deleted is false
				percentage 100%/n
				manual false
			set item.fronter to fronter
			**where** price is not 0
			**then** 
				decrease fronter's outstandingBalance by price - price/n
				increase the outstandingBalance of every user that is not fronter by price/n
			return this Item as item
	setStake(item: Item, shares: Set<Shares>)
		**where** item's price is not 0 
		and no two Shares in shares have the same user
		and the sum of share.percentage for every share in shares is 100%
		and share.percentage is positive for every share in shares
		**then** 
			for every share in item.shares:
				decrease share.user.outstandingBalance by item.price * share.percentage
			for every share in shares:
				increase share.user.outstandingBalance by item.price * share.percentage
			set item.shares to shares
	setStakeIndividual(item: Item, share: Share, user: User)
		**where** item's price is not 0
		and the sum of share.percentage for every share in item.shares where share.manual is false is less than share.percentage
		and share.percentage is positive
		**then**
			let n represent the number of shares in item.shares where share.manual is false
			let shareOldPercentage represent the share in item.shares where share/user is user, or 0 if no such share exists
			let percentageDiff equal share.percentage - shareOldPercentage
			increase user.outstandingBalance by item.price * percentageDiff
			set item.shares[getter(user = user)] to share 
			for every share in item.shares where share.manual is false and share.user is not user:
				decrease user.outstandingBalance by item.price * (percentageDiff / n)
				increase share.percentage by percentageDiff / n
			
	updateItemPrice(item: Item, price: Number) : return (item: Item)
		**then**
			increase item.fronter.outstandingBalance by item.price
			for every share in item.shares:
				decrease share.user.outstandingBalance by item.price * share.percentage
			set item.price to price
			decrease item.fronter.outstandingBalance by item.price
			for every share in item.shares:
				increase share.user.outstandingBalance by item.price * share.percentage
			return the Item as item
	makePayment(payer: User, payee: User, amount: Number)
		**then** 
			decrease payer.outstandingBalance by amount
			increase payee.outstandingBalance by amount
	deleteItem(item: Item, refund: Boolean)
		**then**
			**where** refund is true
			**then**
				for every share in item.shares:
					decrease share.user.outstandingBalance by item.price * share.percentage
			call ItemTracking.deleteItem(item)
```

```
**reactions**
	**when** Request.authenticateUser(name, password, action)
	**then** 
		**where** UserData.authenticateUser(name, password) returns User user
		**then** UserData.performAction(user, action)
```
Note: action may be ANY action defined in UserData, ItemTracking, or StakePaying. Any user can perform any action at any time. New Users can only be created by existing Users. Any User can delete any User. However, users can only call actions with arguments they have access to: Users cannot perform actions as other users becaues they cannot know the password that creates another User's hash, and Users cannot delete logs to conceal any action they have done because there is no way to access them (as auditLogs creates copies that will not do anything permanent if passed to deleteLog). This should be sufficient accountability to prevent and detect malfeasance within the system.

No other reactions are needed for the system: no action in the system needs to happen without direct user input. A sysadmin may manually create the first user, or manually call deleteLogs, neither of which need a reaction to be defined. All other actions in the system should happen because of a user performing some input, and the set of possible inputs a user can produce/know encompasses all actions in the system as described in the preceding paragraph.



### UI Mockup
A UI sketch can be found at [ui-mockup.pdf](ui-mockup.pdf)




# User Journey

Alice and her household recently started using Communal Item Tracker, to better track their communal items and their purchases thereof. She buys a pack of toilet paper and a crate of tissues, and registers them on the platform, and she buys a loaf of banana bread on a whim on her way back. She really likes banana bread, but she doesn't want to keep it all to herself, so she decides to designate it as communal but claim a 50% share, while leaving the other 2 items on their default shares. She is now owed $26 by the household: $10 for banana bread (which cost $20), $10 for tissues (which cost $15), and $6 for toilet paper (which cost $9). She notes on the platform where they all are in the house, so her housemates can find them at their leisure and use them once they check the platform. 

The next day, she falls ill, and realizes she'll be using the bulk of the tissues, and decides to claim a 66% share of them rather than 33%, so she now is owed $21 instead. A couple days later, she asks her housemates to make her whole. Carol had earlier moved to a 0% share of the toilet paper, since she is a divine being who has no bowels and no need of a toilet, meaning that Alice was owed $19.50 (as she now has a 50% share of the TP instead of 33%), with Carol owing her $5 for the banana bread and $2.50 for the tissues and Bob owing her $5 for the banana bread, $2.50 for the issues, and $4.50 for the toilet paper. Bob pays her $12 and Carol pays her $7.50, and all debts are resolved.


