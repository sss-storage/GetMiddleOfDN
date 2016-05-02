# Get Middle Of DN

For example if you want "users" from /blah/users/user123

Use the parsing capability.  starts=-2 will start at the end and go back two the just have a length of 1.
```
<do-set-local-variable name="lvBlLocation" scope="policy">
	<arg-string>
		<token-src-dn length="1" start="-2"/>
	</arg-string>
</do-set-local-variable>
```
