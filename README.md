# Nerdout Server

This is the code base that powers http://pdxnerdout.org

## API

`/create/`:
```javascript
{
	"where": "Side Door",
	"start": "1800",
	"end": "2000"
}
```

`/attend/`:
```javascript
{
	"id": 1823,
	"who": "Wraithan"
}
```

`/end/`:
```javascript
{
	"id": 1823
}
```

`/<id>/`:
```javascript
{
	"id": 1823,
	"where": "Side Door",
	"start": "1800",
	"end": "2000",
	"attendees": ["Wraithan"]
}
```