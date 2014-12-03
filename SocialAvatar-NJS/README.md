

# SocialAvatar-NJS
This is a Eclipse project for the server part used by the Social Avatar implementation. To use it, you must install the Node.js eclipse plugin (http://www.nodeclipse.org/). The project uses a specific FIFO implementation defined by the AWS infrastructure called "SQS - Simple Queue Service". You must configure your SQS queues and use it with your on queues implementations, but generally, only four queues are necessary to be defined for the solution to work:
* One for the Adam Avatar INPUT
* Other for the Eve Avatar INPUT
* Other for the INPUT command queue
* And finally, one for the OUTPUT command queue

All of these queues are used to maintain the flow between the Avatar runtime.


## Usage
As described above.


## Developing
This product is delivered as is.


### Tools

Created with [Nodeclipse](https://github.com/Nodeclipse/nodeclipse-1)
 ([Eclipse Marketplace](http://marketplace.eclipse.org/content/nodeclipse), [site](http://www.nodeclipse.org))   

Nodeclipse is free open-source project that grows with your contributions.
