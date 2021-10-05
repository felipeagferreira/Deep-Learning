# Fake News Detections with NLP

The year is 2051, fake news has drastically destabilized our political system. 70% of Canadians believe at least one of the major conspiracy theories circulating the country at any given time.

A new type of political party has developed (lets call them Party Q), that relies heavily on fake news and country division and fear to win the support of voters. Party Q has been gaining major traction in Canadian politics at all levels, and certain provinces are currently being occupied by Party Q Political candidates.

The current prime-minister is a stable moderate but there are fears around the rising support for the a Party Q opposition even at the federal level.

You've been asked by the Canadian Government to build a proof of concept model to detect fake news. If successful this model will be deployed and applied to every political speech/comment/post made in this country at all levels of government, it will be used for both real-time fact checking, and flagging of facts to be sent to proffessional fact checkers.

The fate of our nation rests in your capable hands.

The prime minister needs 3 results from your model:

Needs to flag false posts ("pants-fire" or "false") with a recall of at least 70% (these will be sent to proffessional fact checkers)
Needs to flag "true" posts with a precision of at least 95% (these will be used in real-time to verify facts during presentations)
Needs to flag "pants-fire" posts with a precision of at least 95% (these will be used in real-time to contradict statements during presentations) (See dataset information for more clarification around labels)
