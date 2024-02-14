# The Invisible Game on the Internet: A Case Study of Decoding Deceptive Patterns

This is the official repository for the paper titled "The Invisible Game on the Internet:
A Case Study of Decoding Deceptive Patterns" which was published at the International World Wide Web Conference 2024 (known as WWW).

In this repository, we provide an Excel spreadsheet that can calculate the risk value by filling in all the features of a given example.



If you have any questions, feel free to submit an issue or email me by zewei.shi@data61.csiro.au



Note: More Case Study will be released soon...

## Explain for each term

* Adv: 

	Human can not detect: The higher value, the more difficult for human to detect.

	*  UI Feature
		* High : UI contain high-risky deceptive features that could mislead or fool a user
		* Medium : UI contain medium-risky deceptive features that could mislead or fool a user
		* Low : UI contain no-risky or low-risky deceptive features that could mislead or fool a user

	* Preliminary Knowledge
		* High: No preliminary knowledge needed
		* Medium: Some people need the preliminary knowledge
		* Low: Lots of people need the preliminary knowledge

	* Sequence
		* High: Invloved dynamic multiple steps
		* Medium: Invloved dynamic two steps
		* Low: Static (A Single image)

* Det: 

	Model can detect: The higher value, the easier for model to detect

	* Hard to detect
	* Easy to detect
	* Have data: There is a accuracy from the SOTA Model

* Impact factor:  (True or False Question)

	How serious the consequences are

	* Time: Will user's time be wasted?
	* Privacy: Will user's privacy data be leaked?
	* Finance: WIll user's money be lost?


## Citing Our Work

If you find our work is beneficial, please cite our work:
```
@misc{shi2024invisible,
      title={The Invisible Game on the Internet: A Case Study of Decoding Deceptive Patterns}, 
      author={Zewei Shi and Ruoxi Sun and Jieshan Chen and Jiamou Sun and Minhui Xue},
      year={2024},
      eprint={2402.03569},
      archivePrefix={arXiv},
      primaryClass={cs.CR}
}
```