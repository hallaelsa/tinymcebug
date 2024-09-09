# tinymce bug in comments

the code of interest is in TinyMceBug => Pages => TinyMceBugPage.razor

The problem is that we are not able to save changes made to a comment and/or if one comment in a conversation is deleted. The ValueChange in the Editor does not respond to these changes.
