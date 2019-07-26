# ![LOGO](logo.png) groupalarm Newshub API **flow**ground Connector

## Description

A generated **flow**ground connector for the groupalarm Newshub API API (version 1.16.0).

Generated from: https://app.groupalarm.com/api/v1<br/>
Generated at: 2019-07-26T13:59:34+03:00

## API Description

The newshub service implements all newshub functions for GroupAlarm<br/>
<br/>
# Authentication<br/>
<br/>
<!-- ReDoc-Inject: <security-definitions> --><br/>

## Authorization

Supported authorization schemes:
- API Key
- API Key

## Actions

### CreateArticle
> Inserts a new article in the newshub (only for admins)<br/>

*Tags:* `newshub`

### GetArticle
> Returns the requested article with the passed id<br/>

*Tags:* `newshub`

#### Input Parameters
* `id` - _required_ - id of the requested article<br/>

### DeleteArticle
> Deletes an article from the newshub (only for admins)<br/>

*Tags:* `newshub`

#### Input Parameters
* `id` - _required_ - id of an article<br/>

### GetArticles
> Returns paginated global articles from the newshub<br/>

*Tags:* `newshub`

#### Input Parameters
* `limit` - _optional_ - max. amount of entries in list<br/>
* `offset` - _optional_ - amount of entries to skip<br/>

### GetPublished
> Returns all paginated published articles from the newshub<br/>

*Tags:* `newshub`

#### Input Parameters
* `limit` - _optional_ - max. amount of entries in list<br/>
* `offset` - _optional_ - amount of entries to skip<br/>

### GetUnreadArticles
> Returns all unread articles from the newshub<br/>

*Tags:* `newshub`

### GetUserReadArticles
> Returns the id of the last read article for the current user<br/>

*Tags:* `newshub`

### UpsertUserReadArticles
> Updates the read articles for the current user<br/>

*Tags:* `newshub`

### AddUserReadArticle
> Adds the passed article id to the read articles for this user<br/>

*Tags:* `newshub`

#### Input Parameters
* `id` - _required_ - id of the read article that should be added for this user<br/>

### GetUserUnreadArticlesCount
> Returns the amount of unread articles for the current user<br/>

*Tags:* `newshub`

## License

**flow**ground :- Telekom iPaaS / groupalarm-newshub-api-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
