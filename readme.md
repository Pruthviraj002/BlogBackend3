{
	"info": {
		"_postman_id": "92fd6c53-f8c9-4b29-87dd-05d4ec375ae0",
		"name": "BlogBackend2",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_exporter_id": "39588880"
	},
	"item": [
		{
			"name": "get-user",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "https://blogbackend3-2ygf.onrender.com/api/user",
					"protocol": "https",
					"host": [
						"blogbackend3-2ygf",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"user"
					]
				}
			},
			"response": []
		},
		{
			"name": "user-post",
			"request": {
				"method": "POST",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"name\":\"sham\",\r\n    \"email\":\"sham@gmail.com\",\r\n    \"password\":\"sham123\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://blogbackend3-2ygf.onrender.com/api/user/login",
					"protocol": "https",
					"host": [
						"blogbackend3-2ygf",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"user",
						"login"
					]
				}
			},
			"response": []
		},
		{
			"name": "get-blog",
			"request": {
				"method": "GET",
				"header": [],
				"url": {
					"raw": "https://blogbackend3-2ygf.onrender.com/api/blog",
					"protocol": "https",
					"host": [
						"blogbackend3-2ygf",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"blog"
					]
				}
			},
			"response": []
		},
		{
			"name": "post-blog",
			"request": {
				"method": "POST",
				"header": [
					{
						"key": "auth-token",
						"value": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJfaWQiOiI2NzMwZWJkNDNkNTE5MmI2YzJiY2Y1YWUiLCJpYXQiOjE3MzEyNTkzNjB9.F6zmGO6RxqTyGHzaxoQM2LdQte7_QKnIT9HPea8HVg4",
						"type": "text"
					}
				],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"title\":\"mahabaleshwar\",\r\n    \"content\":\"recently visited to mahabaleshwar for Trek\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://blogbackend3-2ygf.onrender.com/api/blog",
					"protocol": "https",
					"host": [
						"blogbackend3-2ygf",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"blog"
					]
				}
			},
			"response": []
		},
		{
			"name": "put-blog",
			"request": {
				"method": "PUT",
				"header": [
					{
						"key": "auth-token",
						"value": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJfaWQiOiI2NzMwZWNmMzNkNTE5MmI2YzJiY2Y1YjQiLCJpYXQiOjE3MzEyNTk2NDB9.eka2YDZCbsog14qTo8ojti-8GimbWU8r3dY-6kGV_Jk",
						"type": "text"
					}
				],
				"body": {
					"mode": "raw",
					"raw": "{\r\n     \"title\": \"Enjoying Day\",\r\n            \"content\": \"clg friend day\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://blogbackend3-2ygf.onrender.com/api/blog/672ecbbb60d5ef82b54a4ae4",
					"protocol": "https",
					"host": [
						"blogbackend3-2ygf",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"blog",
						"672ecbbb60d5ef82b54a4ae4"
					]
				}
			},
			"response": []
		},
		{
			"name": "delete-blog",
			"request": {
				"method": "DELETE",
				"header": [
					{
						"key": "auth-token",
						"value": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJfaWQiOiI2NzMwZWNmMzNkNTE5MmI2YzJiY2Y1YjQiLCJpYXQiOjE3MzEyNTk2NDB9.eka2YDZCbsog14qTo8ojti-8GimbWU8r3dY-6kGV_Jk",
						"type": "text"
					}
				],
				"url": {
					"raw": "https://blogbackend3-2ygf.onrender.com/api/blog/672ef8586301e12526aca5f9",
					"protocol": "https",
					"host": [
						"blogbackend3-2ygf",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"blog",
						"672ef8586301e12526aca5f9"
					]
				}
			},
			"response": []
		},
		{
			"name": "put-user",
			"request": {
				"method": "PUT",
				"header": [],
				"body": {
					"mode": "raw",
					"raw": "{\r\n    \"name\": \"Pruthvi\",\r\n            \"email\": \"Pruthvi@gmail.com\",\r\n            \"password\":\"Pruthvi\"\r\n}",
					"options": {
						"raw": {
							"language": "json"
						}
					}
				},
				"url": {
					"raw": "https://blogbackend3-2ygf.onrender.com/api/user/672daa9c1ecb2ee5b1cde4b6",
					"protocol": "https",
					"host": [
						"blogbackend3-2ygf",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"user",
						"672daa9c1ecb2ee5b1cde4b6"
					]
				}
			},
			"response": []
		},
		{
			"name": "delete-user",
			"request": {
				"method": "DELETE",
				"header": [],
				"url": {
					"raw": "https://blogbackend3-2ygf.onrender.com/api/user/672efbe115ae202be6fed2a3",
					"protocol": "https",
					"host": [
						"blogbackend3-2ygf",
						"onrender",
						"com"
					],
					"path": [
						"api",
						"user",
						"672efbe115ae202be6fed2a3"
					]
				}
			},
			"response": []
		}
	]
}
