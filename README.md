# Postman-Crud-Functionality
Showcasing a Project I made; A catelog of my CRUD Functionality 
{
	"info": {
		"_postman_id": "d9f1b9e9-5653-4126-b908-32c1958d1c64",
		"name": "CampDev API",
		"description": "This is a project that catelogs all bootcamps and compares them to asses which one may be right for YOU!",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json"
	},
	"item": [
		{
			"name": "Bootcamps",
			"item": [
				{
					"name": "Get All Bootcamps",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://localhost:3004/api/v1/bootcamps",
							"protocol": "http",
							"host": [
								"localhost"
							],
							"port": "3004",
							"path": [
								"api",
								"v1",
								"bootcamps"
							]
						},
						"description": "This is call for all our bootcamps"
					},
					"response": []
				},
				{
					"name": "Get bootcamp by ID",
					"request": {
						"method": "GET",
						"header": [],
						"url": {
							"raw": "http://localhost:3004/api/v1/bootcamps/3",
							"protocol": "http",
							"host": [
								"localhost"
							],
							"port": "3004",
							"path": [
								"api",
								"v1",
								"bootcamps",
								"3"
							]
						},
						"description": "Getting one bootcamp by ID"
					},
					"response": []
				},
				{
					"name": "Create New Bootcamp",
					"request": {
						"method": "POST",
						"header": [],
						"url": {
							"raw": "http://localhost:3004/api/v1/bootcamps",
							"protocol": "http",
							"host": [
								"localhost"
							],
							"port": "3004",
							"path": [
								"api",
								"v1",
								"bootcamps"
							]
						},
						"description": "Creating a New Bootcamp"
					},
					"response": []
				},
				{
					"name": "Update Bootcamp",
					"request": {
						"method": "PUT",
						"header": [],
						"url": {
							"raw": "http://localhost:3004/api/v1/bootcamps/3",
							"protocol": "http",
							"host": [
								"localhost"
							],
							"port": "3004",
							"path": [
								"api",
								"v1",
								"bootcamps",
								"3"
							]
						},
						"description": "Used to update an entry"
					},
					"response": []
				},
				{
					"name": "Delete a Bootcamp",
					"request": {
						"method": "DELETE",
						"header": [],
						"url": {
							"raw": "http://localhost:3004/api/v1/bootcamps/4",
							"protocol": "http",
							"host": [
								"localhost"
							],
							"port": "3004",
							"path": [
								"api",
								"v1",
								"bootcamps",
								"4"
							]
						},
						"description": "Deleteing an entry by ID"
					},
					"response": []
				}
			],
			"description": "Bootcamps crud functionality"
		}
	]
}
