# Example finding

Use the amount of structure the review needs. A finding should make the problem,
evidence, consequence, and proposed change easy to assess; these are not required
field names or an output schema.

> **The empty search state hides the recovery action.** On `/records`, searching
> for an unmatched value replaces both results and filters with “No records.” I
> reproduced this in the browser; the query remains active, but the clear control
> disappears. Keep the filters visible and offer “Clear search” beside the empty
> message so the user can recover without navigating away.

A screenshot region, selector, or source location can anchor the observation.
Use severity only if helpful, based on the consequence in this product. State
uncertainty when relevant, and separate a taste suggestion from a usability defect.
Combine symptoms addressed by one fix rather than emitting one finding for each
matching catalog entry. Fewer supported findings are better than padding a quota.
