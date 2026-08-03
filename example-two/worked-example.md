# Worked Example Two: A Different Studio, the Other Two Drivers

The first [example](../example/) tests `genuine-fault` and `feeling-unheard`. This one tests the remaining two: `expectation-mismatch`, and a complaint too vague to diagnose at all, where the right move is to stop and ask, not guess.

## Case 3: The Glaze Colour

**Complaint:** "I ordered a mug with a blue glaze and this is nothing like what I wanted."

**What actually happened:** the listing described the glaze as "a blue-toned reactive glaze, colour varies piece to piece", with no specific shade shown or promised. The mug that arrived is a genuine blue-toned reactive glaze, just a different blue than the customer pictured.

**Diagnosis:** `expectation-mismatch`. Nothing was promised that did not happen: the listing was accurate, and reactive glazes varying piece to piece is exactly what was described. The customer expected a specific shade that was never actually committed to.

**Reply:** "Thanks for reaching out, and sorry it's not the shade you had in mind. Reactive glazes do vary piece to piece, which is part of what the listing describes, so I can't promise an exact match to a specific shade. If you'd like, I can look at what's currently in stock and see if anything is closer to what you pictured, or happy to talk through a return if it's not right for you."

**Why this is right:** treating this as `genuine-fault` would mean apologising for a mistake that was not actually made. The listing was accurate; the mismatch is between what was expected and what was actually promised, not a broken commitment.

## Case 4: Too Vague to Diagnose

**Complaint:** "This isn't what I wanted, not happy with this order."

**What is known:** nothing else. No order details, no description of what is wrong, no prior contact.

**Correct response:** stop rather than guess. There is not enough here to distinguish a genuine fault from an expectation mismatch from anything else. Ask for the minimum missing information: which order, and what specifically about it is not right.

**Why this is right:** picking a diagnosis anyway, defaulting to `genuine-fault` because it is the simplest guess, or to `feeling-unheard` because it sounds emotionally safe, would mean answering a complaint that has not actually been described yet. The skill's own stop condition names exactly this case: "the complaint is too vague to distinguish a genuine fault from something else."

## What This Tests

Case 3 checks that an accurate, honoured description does not get treated as a fault just because the customer is unhappy with the result. Case 4 checks that the tool actually stops and asks when there is not enough to diagnose, rather than forcing a plausible-sounding guess onto a one-line complaint.
