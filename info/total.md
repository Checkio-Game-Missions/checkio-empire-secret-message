>"Where does a wise man hide a leaf? In the forest.
>But what does he do if there is no forest? ... He grows a forest to hide it in."

>-- Gilbert Keith Chesterton

Ever tried to send a secret message to someone without using the crypted channel? 
You could use public communication to tell your secret.
Even if someone finds your message, it’s easy to brush them off and that its paranoia and a bogus conspiracy theory.
That's why we would try to use one of this method for squad communication.

You are given a chunk of text. Gather all capital letters in one word in the order that they appear in the text.

For example: text = "**H**ow are you? **E**h, ok. **L**ow or **L**ower? **O**hhh.",
if we collect all of the capital letters, we get the message "HELLO".

**Input:** A text as a string. 

**Output:** The secret message as a string or an empty string.

**Example:**

```python
find_message("How are you? Eh, ok. Low or Lower? Ohhh.") == "HELLO"
find_message("hello world!") == ""
```
**How it is used:**

It's useful

**Precondition:**
```python
0 < len(text) <= 1000
all(ch in string.printable for ch in text)
```
