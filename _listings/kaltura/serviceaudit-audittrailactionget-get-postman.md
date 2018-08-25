{
  "info": {
    "name": "Kaltura VPaaS Get Service Audit Audittrail Action Get",
    "_postman_id": "0b91b9ea-ffa6-4d94-b6df-b69a277cb1a5",
    "description": "Retrieve an audit trail object by id",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Service",
      "item": [
        {
          "id": "4b2b36db-3f44-46eb-b45b-9bc16840f25d",
          "name": "accessControl.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/add?accessControl[description]=%7B%7D&accessControl[isDefault]=%7B%7D&accessControl[name]=%7B%7D&accessControl[restrictions]=%7B%7D&accessControl[systemName]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new Access Control Profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "04031605-857b-4618-b7b7-7a03ab6ef466"
            }
          ]
        },
        {
          "id": "8e033f9b-a0a6-47e4-8087-93ab7650892c",
          "name": "accessControl.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete Access Control Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ba65366a-7b07-4e5c-a1e9-ed1d8ac3f8a5"
            }
          ]
        },
        {
          "id": "dcc8a912-722e-4a93-b4e1-32875f9ee271",
          "name": "accessControl.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Access Control Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4429bb19-677c-48c2-b146-a50ffeecf204"
            }
          ]
        },
        {
          "id": "4c975926-333e-4055-8ddd-7efbe0d538ec",
          "name": "accessControl.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[orderBy]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List Access Control Profiles by filter and pager"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "16e7f446-32b7-4d47-8003-8c68ad7101fe"
            }
          ]
        },
        {
          "id": "0fb3eadb-5b12-4d92-9853-374aa18d2909",
          "name": "accessControl.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrol/action/update?accessControl[description]=%7B%7D&accessControl[isDefault]=%7B%7D&accessControl[name]=%7B%7D&accessControl[restrictions]=%7B%7D&accessControl[systemName]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update Access Control Profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3ed6e4f7-bcda-4dad-b937-4b624e04eb7e"
            }
          ]
        },
        {
          "id": "1e9055ef-b2d6-4395-8304-db9eb1ca4bf7",
          "name": "accessControlProfile.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrolprofile/action/add?accessControlProfile[description]=%7B%7D&accessControlProfile[isDefault]=%7B%7D&accessControlProfile[name]=%7B%7D&accessControlProfile[rules]=%7B%7D&accessControlProfile[systemName]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new access control profile"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "36fed98a-2252-4f6b-93c6-1aa3bfaac39d"
            }
          ]
        },
        {
          "id": "99844755-a1d9-44d7-af7e-ff5a442d0874",
          "name": "accessControlProfile.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrolprofile/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete access control profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ba9db752-e419-485b-b72b-4f11fe6f96cf"
            }
          ]
        },
        {
          "id": "6f12caba-d009-4494-920a-28b5908bbf9a",
          "name": "accessControlProfile.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrolprofile/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get access control profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "ac4cb219-0932-4457-a1c5-aafb52727d60"
            }
          ]
        },
        {
          "id": "580f3492-2d6a-40ae-8744-48adb82ec9c5",
          "name": "accessControlProfile.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrolprofile/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[orderBy]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List access control profiles by filter and pager"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e6055d91-af73-4e1a-9866-b5ab6575087c"
            }
          ]
        },
        {
          "id": "095b1a3c-8acc-4538-9e52-210dee18aedf",
          "name": "accessControlProfile.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/accesscontrolprofile/action/update?accessControlProfile[description]=%7B%7D&accessControlProfile[isDefault]=%7B%7D&accessControlProfile[name]=%7B%7D&accessControlProfile[rules]=%7B%7D&accessControlProfile[systemName]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update access control profile by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27fdadea-d6cf-4237-a754-294c8a9667af"
            }
          ]
        },
        {
          "id": "c810be4d-8f9f-4b67-aaf2-4dd81f2ec80a",
          "name": "adminUser.login",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/adminuser/action/login?email=%7B%7D&No Name=%7B%7D&partnerId=%7B%7D&password=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get an admin session using admin email and password (Used for login to the KMC application)"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b3a3f869-fdc5-49e9-804e-47c56f5807f5"
            }
          ]
        },
        {
          "id": "6e97f3c2-2faa-4d28-b428-a03a063755df",
          "name": "adminUser.resetPassword",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/adminuser/action/resetPassword?email=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Reset admin user password and send it to the users email address"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e626ae7f-d6e0-4d07-b77a-fd8e45b215ac"
            }
          ]
        },
        {
          "id": "783d6338-ff7d-4612-af7d-0d2133d20e78",
          "name": "adminUser.setInitialPassword",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/adminuser/action/setInitialPassword?hashKey=%7B%7D&newPassword=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Set initial users password"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "196cfbc4-0563-45b7-afec-fd20bf73276b"
            }
          ]
        },
        {
          "id": "ef550db9-b32e-40bf-b323-ab313a3d1f00",
          "name": "adminUser.updatePassword",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/adminuser/action/updatePassword?email=%7B%7D&newEmail=%7B%7D&newPassword=%7B%7D&No Name=%7B%7D&password=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update admin user password and email"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "718c1f94-8781-4176-92d3-b6708718a72e"
            }
          ]
        },
        {
          "id": "29fe1cf6-3d47-4e86-865b-aee7e978a2e5",
          "name": "analytics.query",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/analytics/action/query?filter[dimensions]=%7B%7D&filter[filters]=%7B%7D&filter[from_time]=%7B%7D&filter[metrics]=%7B%7D&filter[orderBy]=%7B%7D&filter[to_time]=%7B%7D&filter[utcOffset]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "report query action allows to get a analytics data for specific query dimensions, metrics and filters."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "fd09ae9b-15f5-482c-b808-677da60d3370"
            }
          ]
        },
        {
          "id": "660f79b4-807f-4d80-8f76-8ea59883a304",
          "name": "annotation.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/add?annotation[adType]=%7B%7D&annotation[answerKey]=%7B%7D&annotation[assetId]=%7B%7D&annotation[code]=%7B%7D&annotation[correctAnswerKeys]=%7B%7D&annotation[description]=%7B%7D&annotation[duration]=%7B%7D&annotation[endTime]=%7B%7D&annotation[entryId]=%7B%7D&annotation[eventType]=%7B%7D&annotation[explanation]=%7B%7D&annotation[forceStop]=%7B%7D&annotation[hint]=%7B%7D&annotation[isPublic]=%7B%7D&annotation[objectType]=%7B%7D&annotation[optionalAnswers]=%7B%7D&annotation[parentId]=%7B%7D&annotation[partnerData]=%7B%7D&annotation[partnerSortValue]=%7B%7D&annotation[protocolType]=%7B%7D&annotation[question]=%7B%7D&annotation[quizUserEntryId]=%7B%7D&annotation[searchableOnEntry]=%7B%7D&annotation[sourceUrl]=%7B%7D&annotation[startTime]=%7B%7D&annotation[subType]=%7B%7D&annotation[systemName]=%7B%7D&annotation[tags]=%7B%7D&annotation[text]=%7B%7D&annotation[thumbOffset]=%7B%7D&annotation[title]=%7B%7D&annotation[triggeredAt]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows you to add an annotation object associated with an entry"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "67d02caa-b229-4244-a6bc-2aa22c4ed24f"
            }
          ]
        },
        {
          "id": "3970f4ff-482e-4237-af13-59bb28e37605",
          "name": "annotation.addFromBulk",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/addFromBulk?No Name=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "fileData",
                  "value": "{}",
                  "disabled": false,
                  "description": ""
                }
              ]
            },
            "description": "Allows you to add multiple cue points objects by uploading XML that contains multiple cue point definitions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c1078dcf-ee2a-459c-9292-99df76e4ad23"
            }
          ]
        },
        {
          "id": "a2cbaa43-bbde-40ed-9dc0-4fb0e017c8bd",
          "name": "annotation.clone",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/clone?entryId=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Clone cuePoint with id to given entry"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "620c9490-02fb-4170-840d-41d9800b21b9"
            }
          ]
        },
        {
          "id": "28ede29f-bf3a-442b-b3cc-b46182f14af5",
          "name": "annotation.count",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/count?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[codeEqual]=%7B%7D&filter[codeIn]=%7B%7D&filter[codeLike]=%7B%7D&filter[codeMultiLikeAnd]=%7B%7D&filter[codeMultiLikeOr]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[cuePointTypeEqual]=%7B%7D&filter[cuePointTypeIn]=%7B%7D&filter[descriptionLike]=%7B%7D&filter[descriptionMultiLikeAnd]=%7B%7D&filter[descriptionMultiLikeOr]=%7B%7D&filter[durationGreaterThanOrEqual]=%7B%7D&filter[durationLessThanOrEqual]=%7B%7D&filter[endTimeGreaterThanOrEqual]=%7B%7D&filter[endTimeLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[entryIdIn]=%7B%7D&filter[eventTypeEqual]=%7B%7D&filter[eventTypeIn]=%7B%7D&filter[forceStopEqual]=%7B%7D&filter[freeText]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[isPublicEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[parentIdEqual]=%7B%7D&filter[parentIdIn]=%7B%7D&filter[partnerSortValueEqual]=%7B%7D&filter[partnerSortValueGreaterThanOrEqual]=%7B%7D&filter[partnerSortValueIn]=%7B%7D&filter[partnerSortValueLessThanOrEqual]=%7B%7D&filter[protocolTypeEqual]=%7B%7D&filter[protocolTypeIn]=%7B%7D&filter[questionLike]=%7B%7D&filter[questionMultiLikeAnd]=%7B%7D&filter[questionMultiLikeOr]=%7B%7D&filter[quizUserEntryIdEqual]=%7B%7D&filter[quizUserEntryIdIn]=%7B%7D&filter[startTimeGreaterThanOrEqual]=%7B%7D&filter[startTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[subTypeEqual]=%7B%7D&filter[subTypeIn]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&filter[tagsLike]=%7B%7D&filter[tagsMultiLikeAnd]=%7B%7D&filter[tagsMultiLikeOr]=%7B%7D&filter[textLike]=%7B%7D&filter[textMultiLikeAnd]=%7B%7D&filter[textMultiLikeOr]=%7B%7D&filter[titleLike]=%7B%7D&filter[titleMultiLikeAnd]=%7B%7D&filter[titleMultiLikeOr]=%7B%7D&filter[triggeredAtGreaterThanOrEqual]=%7B%7D&filter[triggeredAtLessThanOrEqual]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[userIdCurrent]=%7B%7D&filter[userIdEqualCurrent]=%7B%7D&filter[userIdEqual]=%7B%7D&filter[userIdIn]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "count cue point objects by filter"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5267bb38-4c2d-46eb-933f-e81533661f76"
            }
          ]
        },
        {
          "id": "91160156-ecc1-45bc-b919-0accd2581b97",
          "name": "annotation.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "delete cue point by id, and delete all children cue points"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "21de4ec9-408b-4d47-9698-a6c71fec305f"
            }
          ]
        },
        {
          "id": "f867c035-12b2-4232-a1f6-75e74ba31bac",
          "name": "annotation.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve an CuePoint object by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4f342e73-bee8-47f7-acb1-9710c7303c50"
            }
          ]
        },
        {
          "id": "5e6a4288-0cd2-4f91-86ab-1c0d991f0e85",
          "name": "annotation.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[codeEqual]=%7B%7D&filter[codeIn]=%7B%7D&filter[codeLike]=%7B%7D&filter[codeMultiLikeAnd]=%7B%7D&filter[codeMultiLikeOr]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[cuePointTypeEqual]=%7B%7D&filter[cuePointTypeIn]=%7B%7D&filter[descriptionLike]=%7B%7D&filter[descriptionMultiLikeAnd]=%7B%7D&filter[descriptionMultiLikeOr]=%7B%7D&filter[durationGreaterThanOrEqual]=%7B%7D&filter[durationLessThanOrEqual]=%7B%7D&filter[endTimeGreaterThanOrEqual]=%7B%7D&filter[endTimeLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[entryIdIn]=%7B%7D&filter[eventTypeEqual]=%7B%7D&filter[eventTypeIn]=%7B%7D&filter[forceStopEqual]=%7B%7D&filter[freeText]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[isPublicEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[parentIdEqual]=%7B%7D&filter[parentIdIn]=%7B%7D&filter[partnerSortValueEqual]=%7B%7D&filter[partnerSortValueGreaterThanOrEqual]=%7B%7D&filter[partnerSortValueIn]=%7B%7D&filter[partnerSortValueLessThanOrEqual]=%7B%7D&filter[protocolTypeEqual]=%7B%7D&filter[protocolTypeIn]=%7B%7D&filter[questionLike]=%7B%7D&filter[questionMultiLikeAnd]=%7B%7D&filter[questionMultiLikeOr]=%7B%7D&filter[quizUserEntryIdEqual]=%7B%7D&filter[quizUserEntryIdIn]=%7B%7D&filter[startTimeGreaterThanOrEqual]=%7B%7D&filter[startTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[subTypeEqual]=%7B%7D&filter[subTypeIn]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&filter[tagsLike]=%7B%7D&filter[tagsMultiLikeAnd]=%7B%7D&filter[tagsMultiLikeOr]=%7B%7D&filter[textLike]=%7B%7D&filter[textMultiLikeAnd]=%7B%7D&filter[textMultiLikeOr]=%7B%7D&filter[titleLike]=%7B%7D&filter[titleMultiLikeAnd]=%7B%7D&filter[titleMultiLikeOr]=%7B%7D&filter[triggeredAtGreaterThanOrEqual]=%7B%7D&filter[triggeredAtLessThanOrEqual]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[userIdCurrent]=%7B%7D&filter[userIdEqualCurrent]=%7B%7D&filter[userIdEqual]=%7B%7D&filter[userIdIn]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List annotation objects by filter and pager"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9db0f6e0-fd6b-4e98-ba63-d2e6f96d9280"
            }
          ]
        },
        {
          "id": "731e0815-3a55-422b-9a3d-feec4e280a00",
          "name": "annotation.serveBulk",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/serveBulk?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[codeEqual]=%7B%7D&filter[codeIn]=%7B%7D&filter[codeLike]=%7B%7D&filter[codeMultiLikeAnd]=%7B%7D&filter[codeMultiLikeOr]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[cuePointTypeEqual]=%7B%7D&filter[cuePointTypeIn]=%7B%7D&filter[descriptionLike]=%7B%7D&filter[descriptionMultiLikeAnd]=%7B%7D&filter[descriptionMultiLikeOr]=%7B%7D&filter[durationGreaterThanOrEqual]=%7B%7D&filter[durationLessThanOrEqual]=%7B%7D&filter[endTimeGreaterThanOrEqual]=%7B%7D&filter[endTimeLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[entryIdIn]=%7B%7D&filter[eventTypeEqual]=%7B%7D&filter[eventTypeIn]=%7B%7D&filter[forceStopEqual]=%7B%7D&filter[freeText]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[isPublicEqual]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[parentIdEqual]=%7B%7D&filter[parentIdIn]=%7B%7D&filter[partnerSortValueEqual]=%7B%7D&filter[partnerSortValueGreaterThanOrEqual]=%7B%7D&filter[partnerSortValueIn]=%7B%7D&filter[partnerSortValueLessThanOrEqual]=%7B%7D&filter[protocolTypeEqual]=%7B%7D&filter[protocolTypeIn]=%7B%7D&filter[questionLike]=%7B%7D&filter[questionMultiLikeAnd]=%7B%7D&filter[questionMultiLikeOr]=%7B%7D&filter[quizUserEntryIdEqual]=%7B%7D&filter[quizUserEntryIdIn]=%7B%7D&filter[startTimeGreaterThanOrEqual]=%7B%7D&filter[startTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[subTypeEqual]=%7B%7D&filter[subTypeIn]=%7B%7D&filter[systemNameEqual]=%7B%7D&filter[systemNameIn]=%7B%7D&filter[tagsLike]=%7B%7D&filter[tagsMultiLikeAnd]=%7B%7D&filter[tagsMultiLikeOr]=%7B%7D&filter[textLike]=%7B%7D&filter[textMultiLikeAnd]=%7B%7D&filter[textMultiLikeOr]=%7B%7D&filter[titleLike]=%7B%7D&filter[titleMultiLikeAnd]=%7B%7D&filter[titleMultiLikeOr]=%7B%7D&filter[triggeredAtGreaterThanOrEqual]=%7B%7D&filter[triggeredAtLessThanOrEqual]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&filter[userIdCurrent]=%7B%7D&filter[userIdEqualCurrent]=%7B%7D&filter[userIdEqual]=%7B%7D&filter[userIdIn]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Download multiple cue points objects as XML definitions"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1529b848-b5c6-4c16-bebe-497376d782e8"
            }
          ]
        },
        {
          "id": "ee6aae37-5652-404a-a8f9-351b78224935",
          "name": "annotation.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/update?annotation[adType]=%7B%7D&annotation[answerKey]=%7B%7D&annotation[assetId]=%7B%7D&annotation[code]=%7B%7D&annotation[correctAnswerKeys]=%7B%7D&annotation[description]=%7B%7D&annotation[duration]=%7B%7D&annotation[endTime]=%7B%7D&annotation[entryId]=%7B%7D&annotation[eventType]=%7B%7D&annotation[explanation]=%7B%7D&annotation[forceStop]=%7B%7D&annotation[hint]=%7B%7D&annotation[isPublic]=%7B%7D&annotation[objectType]=%7B%7D&annotation[optionalAnswers]=%7B%7D&annotation[parentId]=%7B%7D&annotation[partnerData]=%7B%7D&annotation[partnerSortValue]=%7B%7D&annotation[protocolType]=%7B%7D&annotation[question]=%7B%7D&annotation[quizUserEntryId]=%7B%7D&annotation[searchableOnEntry]=%7B%7D&annotation[sourceUrl]=%7B%7D&annotation[startTime]=%7B%7D&annotation[subType]=%7B%7D&annotation[systemName]=%7B%7D&annotation[tags]=%7B%7D&annotation[text]=%7B%7D&annotation[thumbOffset]=%7B%7D&annotation[title]=%7B%7D&annotation[triggeredAt]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update annotation by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c9a4f15f-3d2d-4d9a-a1e7-5a1c4f4a9be6"
            }
          ]
        },
        {
          "id": "c8d80bfd-fbbc-4e65-bcc7-7e294162a9f9",
          "name": "annotation.updateStatus",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/annotation_annotation/action/updateStatus?id=%7B%7D&No Name=%7B%7D&status=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update cuePoint status by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "41a0a66e-a2bd-4915-a3a3-e984d23e0a9b"
            }
          ]
        },
        {
          "id": "cedd5ccd-5098-4aab-931a-5ba97edda1ec",
          "name": "appToken.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/add?appToken[expiry]=%7B%7D&appToken[hashType]=%7B%7D&appToken[sessionDuration]=%7B%7D&appToken[sessionPrivileges]=%7B%7D&appToken[sessionType]=%7B%7D&appToken[sessionUserId]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add new application authentication token"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3e83a2b8-a5a5-4be5-a29e-5566e2b03843"
            }
          ]
        },
        {
          "id": "efc92cf0-2c7a-47d2-89d7-b9a6801897ce",
          "name": "appToken.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/delete?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Delete application authentication token by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e9b3ac82-d01c-487a-8c9c-59ff5c429413"
            }
          ]
        },
        {
          "id": "6deb2676-dddf-4ad3-9d33-feb6312e8727",
          "name": "appToken.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get application authentication token by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "dbfa9ea4-1c3e-40b8-bc2c-03ac23feeb08"
            }
          ]
        },
        {
          "id": "4f7f6ada-5b4b-445f-ac5c-aff25e3ddf1e",
          "name": "appToken.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[orderBy]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List application authentication tokens by filter and pager"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "91559a4b-9f52-40e4-b8cf-8110334b0a62"
            }
          ]
        },
        {
          "id": "a127227d-3851-445b-b00d-324f2dcf4574",
          "name": "appToken.startSession",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/startSession?expiry=%7B%7D&id=%7B%7D&No Name=%7B%7D&tokenHash=%7B%7D&type=%7B%7D&userId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Starts a new KS (kaltura Session) based on application authentication token id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cc02f01e-808d-4b64-bc48-6223ba9b05b0"
            }
          ]
        },
        {
          "id": "fcd46e21-0188-4d60-880f-3e043a972a6d",
          "name": "appToken.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/apptoken/action/update?appToken[expiry]=%7B%7D&appToken[hashType]=%7B%7D&appToken[sessionDuration]=%7B%7D&appToken[sessionPrivileges]=%7B%7D&appToken[sessionType]=%7B%7D&appToken[sessionUserId]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update application authentication token by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "0fd284c0-776f-462a-b537-dea56fbaebe9"
            }
          ]
        },
        {
          "id": "276995f6-757e-4e49-a249-3ef53e88fe86",
          "name": "aspera.getFaspUrl",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/aspera_aspera/action/getFaspUrl?flavorAssetId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Service Aspera Aspera Action Getfaspurl"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "d5fb82ba-ed9b-4ad6-82ef-89aebef4b360"
            }
          ]
        },
        {
          "id": "a01c0660-7f72-44c5-99dd-0038626bdcd3",
          "name": "attachmentAsset.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/add?attachmentAsset[accuracy]=%7B%7D&attachmentAsset[actualSourceAssetParamsIds]=%7B%7D&attachmentAsset[fileExt]=%7B%7D&attachmentAsset[filename]=%7B%7D&attachmentAsset[format]=%7B%7D&attachmentAsset[humanVerified]=%7B%7D&attachmentAsset[language]=%7B%7D&attachmentAsset[objectType]=%7B%7D&attachmentAsset[partnerData]=%7B%7D&attachmentAsset[partnerDescription]=%7B%7D&attachmentAsset[providerType]=%7B%7D&attachmentAsset[tags]=%7B%7D&attachmentAsset[title]=%7B%7D&entryId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Add attachment asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "eda0c720-49d5-4354-b448-75a10da783ed"
            }
          ]
        },
        {
          "id": "f95e7604-d838-4a39-8504-7969a5e8a047",
          "name": "attachmentAsset.delete",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/delete?attachmentAssetId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Service Attachment Attachmentasset Action Delete"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "adc506de-a809-4ee7-9ca7-6ea727203c8c"
            }
          ]
        },
        {
          "id": "e73e687b-8166-4f44-8fa7-0e9c524cf13f",
          "name": "attachmentAsset.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/get?attachmentAssetId=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Service Attachment Attachmentasset Action Get"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "441fe638-38eb-464c-91e9-965d61f0a525"
            }
          ]
        },
        {
          "id": "74466f4c-a032-48ac-8c10-d1180c0843a4",
          "name": "attachmentAsset.getRemotePaths",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/getRemotePaths?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get remote storage existing paths for the asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "27200ecc-b499-438d-b43d-2752404c9cf9"
            }
          ]
        },
        {
          "id": "a881838c-34d2-4c49-af8e-a19d059811ce",
          "name": "attachmentAsset.getUrl",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/getUrl?id=%7B%7D&No Name=%7B%7D&storageId=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get download URL for the asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e36e4d00-6329-4ccd-8af9-6208de8e5356"
            }
          ]
        },
        {
          "id": "f260320e-487d-461d-af14-719da5da6322",
          "name": "attachmentAsset.list",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/list?filter[advancedSearch][attribute]=%7B%7D&filter[advancedSearch][categoriesMatchOr]=%7B%7D&filter[advancedSearch][categoryEntryStatusIn]=%7B%7D&filter[advancedSearch][categoryIdEqual]=%7B%7D&filter[advancedSearch][comparison]=%7B%7D&filter[advancedSearch][contentLike]=%7B%7D&filter[advancedSearch][contentMultiLikeAnd]=%7B%7D&filter[advancedSearch][contentMultiLikeOr]=%7B%7D&filter[advancedSearch][cuePointsFreeText]=%7B%7D&filter[advancedSearch][cuePointSubTypeEqual]=%7B%7D&filter[advancedSearch][cuePointTypeIn]=%7B%7D&filter[advancedSearch][depthGreaterThanEqual]=%7B%7D&filter[advancedSearch][distributionProfileId]=%7B%7D&filter[advancedSearch][distributionSunStatus]=%7B%7D&filter[advancedSearch][entryDistributionFlag]=%7B%7D&filter[advancedSearch][entryDistributionStatus]=%7B%7D&filter[advancedSearch][entryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][extendedStatusEqual]=%7B%7D&filter[advancedSearch][extendedStatusIn]=%7B%7D&filter[advancedSearch][field]=%7B%7D&filter[advancedSearch][hasEntryDistributionValidationErrors]=%7B%7D&filter[advancedSearch][idEqual]=%7B%7D&filter[advancedSearch][idIn]=%7B%7D&filter[advancedSearch][indexIdGreaterThan]=%7B%7D&filter[advancedSearch][isQuiz]=%7B%7D&filter[advancedSearch][items]=%7B%7D&filter[advancedSearch][memberIdEq]=%7B%7D&filter[advancedSearch][memberIdIn]=%7B%7D&filter[advancedSearch][memberPermissionsMatchAnd]=%7B%7D&filter[advancedSearch][memberPermissionsMatchOr]=%7B%7D&filter[advancedSearch][metadataProfileId]=%7B%7D&filter[advancedSearch][noDistributionProfiles]=%7B%7D&filter[advancedSearch][not]=%7B%7D&filter[advancedSearch][objectType]=%7B%7D&filter[advancedSearch][orderBy]=%7B%7D&filter[advancedSearch][type]=%7B%7D&filter[advancedSearch][updatedAtGreaterThanOrEqual]=%7B%7D&filter[advancedSearch][updatedAtLessThanOrEqual]=%7B%7D&filter[advancedSearch][userIdEqual]=%7B%7D&filter[advancedSearch][userIdIn]=%7B%7D&filter[advancedSearch][value]=%7B%7D&filter[advancedSearch][watermarkId]=%7B%7D&filter[captionParamsIdEqual]=%7B%7D&filter[captionParamsIdIn]=%7B%7D&filter[contentLike]=%7B%7D&filter[contentMultiLikeAnd]=%7B%7D&filter[contentMultiLikeOr]=%7B%7D&filter[createdAtGreaterThanOrEqual]=%7B%7D&filter[createdAtLessThanOrEqual]=%7B%7D&filter[deletedAtGreaterThanOrEqual]=%7B%7D&filter[deletedAtLessThanOrEqual]=%7B%7D&filter[endTimeGreaterThanOrEqual]=%7B%7D&filter[endTimeLessThanOrEqual]=%7B%7D&filter[entryIdEqual]=%7B%7D&filter[entryIdIn]=%7B%7D&filter[flavorParamsIdEqual]=%7B%7D&filter[flavorParamsIdIn]=%7B%7D&filter[formatEqual]=%7B%7D&filter[formatIn]=%7B%7D&filter[idEqual]=%7B%7D&filter[idIn]=%7B%7D&filter[labelEqual]=%7B%7D&filter[labelIn]=%7B%7D&filter[languageEqual]=%7B%7D&filter[languageIn]=%7B%7D&filter[objectType]=%7B%7D&filter[orderBy]=%7B%7D&filter[partnerDescriptionLike]=%7B%7D&filter[partnerDescriptionMultiLikeAnd]=%7B%7D&filter[partnerDescriptionMultiLikeOr]=%7B%7D&filter[partnerIdEqual]=%7B%7D&filter[partnerIdIn]=%7B%7D&filter[sizeGreaterThanOrEqual]=%7B%7D&filter[sizeLessThanOrEqual]=%7B%7D&filter[startTimeGreaterThanOrEqual]=%7B%7D&filter[startTimeLessThanOrEqual]=%7B%7D&filter[statusEqual]=%7B%7D&filter[statusIn]=%7B%7D&filter[statusNotIn]=%7B%7D&filter[tagsLike]=%7B%7D&filter[tagsMultiLikeAnd]=%7B%7D&filter[tagsMultiLikeOr]=%7B%7D&filter[thumbParamsIdEqual]=%7B%7D&filter[thumbParamsIdIn]=%7B%7D&filter[typeIn]=%7B%7D&filter[updatedAtGreaterThanOrEqual]=%7B%7D&filter[updatedAtLessThanOrEqual]=%7B%7D&No Name=%7B%7D&pager[pageIndex]=%7B%7D&pager[pageSize]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "List attachment Assets by filter and pager"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a593defd-d18b-4d3e-82ef-926ab644bdce"
            }
          ]
        },
        {
          "id": "82fa5955-3548-4d0b-87e0-dc7991095d31",
          "name": "attachmentAsset.serve",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/serve?attachmentAssetId=%7B%7D&No Name=%7B%7D&serveOptions[download]=%7B%7D&serveOptions[referrer]=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Serves attachment by its id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "1ad11c81-2587-4a5e-9cef-45deb054c7d9"
            }
          ]
        },
        {
          "id": "7843f262-f716-4546-a420-f1792ee1c796",
          "name": "attachmentAsset.setContent",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/setContent?contentResource[assetId]=%7B%7D&contentResource[content]=%7B%7D&contentResource[dropFolderFileId]=%7B%7D&contentResource[entryId]=%7B%7D&contentResource[fileSyncObjectType]=%7B%7D&contentResource[flavorParamsId]=%7B%7D&contentResource[forceAsyncDownload]=%7B%7D&contentResource[keepOriginalFile]=%7B%7D&contentResource[keyPassphrase]=%7B%7D&contentResource[localFilePath]=%7B%7D&contentResource[objectId]=%7B%7D&contentResource[objectSubType]=%7B%7D&contentResource[objectType]=%7B%7D&contentResource[privateKey]=%7B%7D&contentResource[publicKey]=%7B%7D&contentResource[resources]=%7B%7D&contentResource[resource][assetId]=%7B%7D&contentResource[resource][content]=%7B%7D&contentResource[resource][dropFolderFileId]=%7B%7D&contentResource[resource][entryId]=%7B%7D&contentResource[resource][fileSyncObjectType]=%7B%7D&contentResource[resource][flavorParamsId]=%7B%7D&contentResource[resource][forceAsyncDownload]=%7B%7D&contentResource[resource][keepOriginalFile]=%7B%7D&contentResource[resource][keyPassphrase]=%7B%7D&contentResource[resource][localFilePath]=%7B%7D&contentResource[resource][objectId]=%7B%7D&contentResource[resource][objectSubType]=%7B%7D&contentResource[resource][objectType]=%7B%7D&contentResource[resource][privateKey]=%7B%7D&contentResource[resource][publicKey]=%7B%7D&contentResource[resource][resources]=%7B%7D&contentResource[resource][resource][assetId]=%7B%7D&contentResource[resource][resource][content]=%7B%7D&contentResource[resource][resource][dropFolderFileId]=%7B%7D&contentResource[resource][resource][entryId]=%7B%7D&contentResource[resource][resource][fileSyncObjectType]=%7B%7D&contentResource[resource][resource][flavorParamsId]=%7B%7D&contentResource[resource][resource][forceAsyncDownload]=%7B%7D&contentResource[resource][resource][keepOriginalFile]=%7B%7D&contentResource[resource][resource][keyPassphrase]=%7B%7D&contentResource[resource][resource][localFilePath]=%7B%7D&contentResource[resource][resource][objectId]=%7B%7D&contentResource[resource][resource][objectSubType]=%7B%7D&contentResource[resource][resource][objectType]=%7B%7D&contentResource[resource][resource][privateKey]=%7B%7D&contentResource[resource][resource][publicKey]=%7B%7D&contentResource[resource][resource][resources]=%7B%7D&contentResource[resource][resource][resource][assetId]=%7B%7D&contentResource[resource][resource][resource][content]=%7B%7D&contentResource[resource][resource][resource][dropFolderFileId]=%7B%7D&contentResource[resource][resource][resource][entryId]=%7B%7D&contentResource[resource][resource][resource][fileSyncObjectType]=%7B%7D&contentResource[resource][resource][resource][flavorParamsId]=%7B%7D&contentResource[resource][resource][resource][forceAsyncDownload]=%7B%7D&contentResource[resource][resource][resource][keepOriginalFile]=%7B%7D&contentResource[resource][resource][resource][keyPassphrase]=%7B%7D&contentResource[resource][resource][resource][localFilePath]=%7B%7D&contentResource[resource][resource][resource][objectId]=%7B%7D&contentResource[resource][resource][resource][objectSubType]=%7B%7D&contentResource[resource][resource][resource][objectType]=%7B%7D&contentResource[resource][resource][resource][privateKey]=%7B%7D&contentResource[resource][resource][resource][publicKey]=%7B%7D&contentResource[resource][resource][resource][resources]=%7B%7D&contentResource[resource][resource][resource][storageProfileId]=%7B%7D&contentResource[resource][resource][resource][token]=%7B%7D&contentResource[resource][resource][resource][url]=%7B%7D&contentResource[resource][resource][resource][version]=%7B%7D&contentResource[resource][resource][storageProfileId]=%7B%7D&contentResource[resource][resource][token]=%7B%7D&contentResource[resource][resource][url]=%7B%7D&contentResource[resource][resource][version]=%7B%7D&contentResource[resource][storageProfileId]=%7B%7D&contentResource[resource][token]=%7B%7D&contentResource[resource][url]=%7B%7D&contentResource[resource][version]=%7B%7D&contentResource[storageProfileId]=%7B%7D&contentResource[token]=%7B%7D&contentResource[url]=%7B%7D&contentResource[version]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "urlencoded",
              "urlencoded": [
                {
                  "key": "contentResource[fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                },
                {
                  "key": "contentResource[resource][resource][resource][fileData]",
                  "value": "{}",
                  "disabled": false,
                  "description": "Represents the $_FILE"
                }
              ]
            },
            "description": "Update content of attachment asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "7af04aad-7e10-45f5-9bdc-3917f0f3d0ab"
            }
          ]
        },
        {
          "id": "25ad6a12-37b3-426e-ade9-64f0bbcede30",
          "name": "attachmentAsset.update",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attachment_attachmentasset/action/update?attachmentAsset[accuracy]=%7B%7D&attachmentAsset[actualSourceAssetParamsIds]=%7B%7D&attachmentAsset[fileExt]=%7B%7D&attachmentAsset[filename]=%7B%7D&attachmentAsset[format]=%7B%7D&attachmentAsset[humanVerified]=%7B%7D&attachmentAsset[language]=%7B%7D&attachmentAsset[objectType]=%7B%7D&attachmentAsset[partnerData]=%7B%7D&attachmentAsset[partnerDescription]=%7B%7D&attachmentAsset[providerType]=%7B%7D&attachmentAsset[tags]=%7B%7D&attachmentAsset[title]=%7B%7D&id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Update attachment asset"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "63e5adba-bf35-4695-8a93-e8af16c79c17"
            }
          ]
        },
        {
          "id": "54e64383-bab0-4a9d-9349-c1b7ea2bae1b",
          "name": "attUverse.getFeed",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/attuversedistribution_attuverse/action/getFeed?distributionProfileId=%7B%7D&hash=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Get Service Attuversedistribution Attuverse Action Getfeed"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "59b2c627-4170-40e8-8774-f91092d6bb4c"
            }
          ]
        },
        {
          "id": "e4f06d40-b091-4100-9a76-cea5e2de7766",
          "name": "auditTrail.add",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/audit_audittrail/action/add?auditTrail[action]=%7B%7D&auditTrail[auditObjectType]=%7B%7D&auditTrail[data][changedItems]=%7B%7D&auditTrail[data][dc]=%7B%7D&auditTrail[data][fileType]=%7B%7D&auditTrail[data][info]=%7B%7D&auditTrail[data][objectSubType]=%7B%7D&auditTrail[data][objectType]=%7B%7D&auditTrail[data][original]=%7B%7D&auditTrail[data][version]=%7B%7D&auditTrail[entryId]=%7B%7D&auditTrail[objectId]=%7B%7D&auditTrail[relatedObjectId]=%7B%7D&auditTrail[relatedObjectType]=%7B%7D&auditTrail[userId]=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Allows you to add an audit trail object and audit trail content associated with Kaltura object"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "328a0f58-03fb-4ab0-9934-8166127cc352"
            }
          ]
        },
        {
          "id": "95991af4-17b7-4cc1-9233-4e0ab1d2bf42",
          "name": "auditTrail.get",
          "request": {
            "url": "http://www.kaltura.com/api_v3/service/audit_audittrail/action/get?id=%7B%7D&No Name=%7B%7D",
            "method": "GET",
            "body": {
              "mode": "raw"
            },
            "description": "Retrieve an audit trail object by id"
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6d908803-0681-4d2d-a65d-e6ebde29589a"
            }
          ]
        }
      ]
    }
  ]
}