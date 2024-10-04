Machine learning using neural networks is evolving at a rapid rate, and
models trained using these networks require increasingly larger data sets to
grow their capabilities. The use of publicly available data sets and internet
scraping techniques are a cheap and easy method to acquire data, but using
these sources renders the trained models vulnerable to malicious poisoning
attacks. One such attack, known as a "clean label" attack, does not require
the attacker to alter data labels or have access to the training data. Instead,
the attacker chooses to "poison" the data itself in the form of a subtle data
alteration capable of escaping the notice of an auditor or labeling processor.
Specifically, the one-shot image alteration poisoning attack demonstrated
in the famous "Poison Frogs" paper was employed to poison a pre-trained
(and also fully trained) neural network trained to recognize traffic signs. This
data set and model were resistant to this form of attack, so the amount of
accuracy degradation on a frozen versus an unfrozen neural network model
were compared, as well as the effects of single class versus multi-class images.
This form attack is highly unlikely to succeed in a dataset containing multiple
instances of each class.
